# Gata

Gata provides a GitHub Copilot custom agent profile for repository-focused software development.

## The `genius` agent

The profile is defined in [`.github/agents/my-agent.agent.md`](.github/agents/my-agent.agent.md). It guides Copilot to inspect repository conventions, make scoped code changes, and run relevant checks when available. For security-related requests, it is intended for defensive analysis, remediation, and authorized testing.

To use it, keep the profile on the repository's default branch and select **genius** from the custom-agent options in a supported Copilot interface. Availability may vary by Copilot product and configuration.

This repository contains the agent profile; it does not provide an application, build, or test command of its own.
