# Quake III DeFRaG Physics (WIP)

[![build](../../workflows/build/badge.svg)](../../actions?query=workflow%3Abuild) <a href="https://discord.com/invite/ZG4dKNVQJu"><img src="https://img.shields.io/discord/751483934034100274?color=7289da&logo=discord&logoColor=white" alt="Discord server" /></a>

This document is a continuous effort to accurately describe the physics of the Quake III mod DeFRaG and explain how the underlying code influences gameplay. It covers fundamental concepts such as input, friction and acceleration, and explores advanced techniques like strafing on different surfaces (e.g., flat, sloped, slick) in various environments (e.g., air, water, flight). Additionally, it delves into the math behind the CGazHUD and SnapHUD, providing a deeper understanding of their displays and the rationale behind them.

Sections will be added or expanded over time.

| [Download latest PDF.](../../releases/download/latest/main.pdf) |
| --------------------------------------------------------------- |

## Building

To generate the PDF, use the following command:

    latexmk -pdflua -shell-escape -synctex=1 -interaction=nonstopmode main.tex
