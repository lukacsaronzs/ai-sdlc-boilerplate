# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Changelog-writer agent for automated CHANGELOG.md maintenance before commits
- Conventional commit rule in `.claude/rules/conventional-commit.mdc`
- Custom `/commit` command for automated git commits
- Repository-level git user configuration

### Changed
- Updated `/commit` command to invoke changelog-writer agent before creating commits
- Simplified commit command to reference conventional-commit rule

### Documentation
- Added CLAUDE.md with project guidelines
- Initial project setup and documentation
