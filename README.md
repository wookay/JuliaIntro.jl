# JuliaIntro

Linux, OSX: [![Build Status](https://api.travis-ci.org/wookay/JuliaIntro.jl.svg?branch=master)](https://travis-ci.org/wookay/JuliaIntro.jl)
Windows: [![Build status](https://ci.appveyor.com/api/projects/status/2994802kg4s9g4av?svg=true)](https://ci.appveyor.com/project/wookay/JuliaIntro.jl)
[![Coverage Status](https://coveralls.io/repos/wookay/JuliaIntro.jl/badge.svg?branch=master&service=github)](https://coveralls.io/github/wookay/JuliaIntro.jl?branch=master)

* 근본주의자 스타일로 줄리아 소개하기

```julia
~/work/JuliaIntro.jl master$ cd src/
~/work/JuliaIntro.jl/src master$ julia
               _
   _       _ _(_)_     |  A fresh approach to technical computing
  (_)     | (_) (_)    |  Documentation: http://docs.julialang.org
   _ _   _| |_  __ _   |  Type "?help" for help.
  | | | | | | |/ _` |  |
  | | |_| | | | (_| |  |  Version 0.4.0-dev+6851 (2015-08-20 08:25 UTC)
 _/ |\__'_|_|_|\__'_|  |  Commit 437f4e9 (0 days old master)
|__/                   |  x86_64-apple-darwin14.4.0

julia> push!(LOAD_PATH, ".")
3-element Array{ByteString,1}:
 "/Users/wookyoung/work/julia/usr/local/share/julia/site/v0.4"
 "/Users/wookyoung/work/julia/usr/share/julia/site/v0.4"
 "."

julia> using JuliaIntro
     module JuliaIntro
    ≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡

julia> @next

     Julia
    ≡≡≡≡≡≡≡

  2015-08-20

julia> @first
     module JuliaIntro
    ≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡

julia> @step 3
3

julia> @page
1:3:58

julia> @next

     JuliaCon
    ≡≡≡≡≡≡≡≡≡≡

    •  http://juliacon.org/
     JuliaCon 2014
    ≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡

    •  http://juliacon.org/2014/
     JuliaCon 2015
    ≡≡≡≡≡≡≡≡≡≡≡≡≡≡≡

    •  http://juliacon.org/2015/
```

# 짤 보기
 * iTerm2 Build 2.9.20150626 beta http://iterm2.com/downloads.html
 * Go
```
julia> run(`go version`)
go version go1.4.2 darwin/amd64
```
