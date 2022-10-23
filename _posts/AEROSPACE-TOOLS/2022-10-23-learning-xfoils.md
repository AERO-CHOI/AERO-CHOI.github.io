---
title: XFOIL의 기초
author: Jonny Choi
date: 2022-10-23 03:00:00 +0900
categories: [Aerospace Tools, Xfoils]
tags: [xfoils]
pin : false
math: true
mermaid: true
---

# XFOIL
## 1. XFOIL의 목적
Subsonic isolated airfoils를 디자인하고 분석하기 위한 툴이다. 본 문서는 [XFOIL 공식 문서](http://web.mit.edu/drela/Public/web/xfoil/)를 기반으로 작성하였다. 원하는 NACA의 DATASHEET를 얻어 분석해보고자 한다.

* Viscous (or inviscid) analysis of an existing airfoil, allowing
  - forced or free transition
  - transitional separation bubbles
  - limited trailing edge separation
  - lift and drag predictions just beyond CLmax
  - Karman-Tsien compressibility correction
  - fixed or varying Reynolds and/or Mach numbers

* Airfoil design and redesign by interactive modification of surface speed distributions, in two methods:
  - Full-Inverse method, based on a complex-mapping formulation
  - Mixed-Inverse method, an extension of XFOIL's basic panel method

* Airfoil redesign by interactive modification of geometric parameters such as
  - max thickness and camber, highpoint position
  - LE radius, TE thickness
  - camber line via geometry specification
  - camber line via loading change specification
  - flap deflection
  - explicit contour geometry (via screen cursor)

* Blending of airfoils

* Writing and reading of airfoil coordinates and polar save files

* Plotting of geometry, pressure distributions, and multiple polars


## 2. XFOIL의 설치
MIT에서 제작한 프로그램이며 GNU General Public License에 따라 배포되고 있다. 다운로드 링크는 [XFOIL 다운로드](http://web.mit.edu/drela/Public/web/xfoil/)이며 Software 단락에서 설치할 수 있다. 이 문서는 xfoil6.97.tar.gz 기준으로 작성하였다.


