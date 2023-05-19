# Sage Assistant Crystal Reports

![Github Version](https://img.shields.io/github/v/release/hks2002/sage-assistant-reports?display_name=release)
![Github Build Status](https://img.shields.io/github/actions/workflow/status/hks2002/sage-assistant-reports/Release-Please.yml)
![GitHub License](https://img.shields.io/github/license/hks2002/sage-assistant-reports)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)
[![release-please: angular](https://img.shields.io/badge/release--please-angular-e10079??style=flat&logo=google)](https://github.com/google-github-actions/release-please-action)

[English](./README.md) | [简体中文](./README.zh-cn.md)

## Change report from sage

1. Remove unused parameters
2. Get result sql
3. Change sql field form style SORDER.SOHNUM_0 to "SORDER.SOHNUM_0 AS SORDER.SOHNUM_0"
4. Add Command with the new sql to Crystal report
5. Replace the fields with "Command.SORDER.SOHNUM_0", using Report Explorer and Data Explorer, don't modify the layout
6. After all fields replaced, remove all old tables.
