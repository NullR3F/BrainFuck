local v0 = string.char
local v1 = string.byte
local v2 = string.sub
local v3 = bit32 or bit
local v4 = v3.bxor
local v5 = table.concat
local v6 = table.insert
local function v7(v24, v25)
    local v26 = {}
    for v41 = 1, #v24 do
        v6(v26, v0(v4(v1(v2(v24, v41, v41 + 1)), v1(v2(v25, 1 + (v41 % #v25), 1 + (v41 % #v25) + 1))) % 256))
    end
    return v5(v26)
end
local v8 = tonumber
local v9 = string.byte
local v10 = string.char
local v11 = string.sub
local v12 = string.gsub
local v13 = string.rep
local v14 = table.concat
local v15 = table.insert
local v16 = math.ldexp
local v17 = getfenv or function()
        return _ENV
    end
local v18 = setmetatable
local v19 = pcall
local v20 = select
local v21 = unpack or table.unpack
local v22 = tonumber
local function v23(v27, v28, ...)
    local v29 = 1
    local v30
    v27 =
        v12(
        v11(v27, 5),
        v7("\124\72", "\97\82\102\90\222"),
        function(v42)
            if (v9(v42, 2) == 79) then
                local v101 = 0
                while true do
                    if (0 == v101) then
                        v30 = v8(v11(v42, 2 - 1, 1))
                        return ""
                    end
                end
            else
                local v102 = v10(v8(v42, 16))
                if v30 then
                    local v110 = 0
                    local v111
                    while true do
                        if (0 == v110) then
                            v111 = v13(v102, v30)
                            v30 = nil
                            v110 = 1
                        end
                        if (v110 == 1) then
                            return v111
                        end
                    end
                else
                    return v102
                end
            end
        end
    )
    local function v31(v43, v44, v45)
        if v45 then
            local v103 = 0
            local v104
            while true do
                if (v103 == 0) then
                    v104 = (v43 / (2 ^ (v44 - 1))) % (2 ^ (((v45 - 1) - (v44 - (2 - 1))) + 1))
                    return v104 - (v104 % 1)
                end
            end
        else
            local v105 = 0
            local v106
            while true do
                if (v105 == 0) then
                    v106 = 2 ^ (v44 - 1)
                    return (((v43 % (v106 + v106)) >= v106) and (1 - 0)) or 0
                end
            end
        end
    end
    local function v32()
        local v46 = v9(v27, v29, v29)
        v29 = v29 + (2 - 1)
        return v46
    end
    local function v33()
        local v47 = 0
        local v48
        local v49
        while true do
            if (v47 == 1) then
                return (v49 * 256) + v48
            end
            if (0 == v47) then
                v48, v49 = v9(v27, v29, v29 + (621 - (555 + 64)))
                v29 = v29 + (933 - (857 + 74))
                v47 = 1
            end
        end
    end
    local function v34()
        local v50, v51, v52, v53 = v9(v27, v29, v29 + 3)
        v29 = v29 + 4
        return (v53 * 16777216) + (v52 * (66104 - (367 + 201))) + (v51 * 256) + v50
    end
    local function v35()
        local v54 = 0
        local v55
        local v56
        local v57
        local v58
        local v59
        local v60
        while true do
            if (v54 == 1) then
                v57 = 928 - (214 + 713)
                v58 = (v31(v56, 1, 20) * (2 ^ 32)) + v55
                v54 = 2
            end
            if (v54 == 0) then
                v55 = v34()
                v56 = v34()
                v54 = 1
            end
            if (v54 == 3) then
                if (v59 == 0) then
                    if (v58 == 0) then
                        return v60 * 0
                    else
                        v59 = 1
                        v57 = 0
                    end
                elseif (v59 == 2047) then
                    return ((v58 == 0) and (v60 * (1 / (0 + 0)))) or (v60 * NaN)
                end
                return v16(v60, v59 - 1023) * (v57 + (v58 / ((879 - (282 + 595)) ^ (1689 - (1523 + 114)))))
            end
            if (v54 == 2) then
                v59 = v31(v56, 21, 31)
                v60 = ((v31(v56, 32) == 1) and -1) or (1 + 0)
                v54 = 3
            end
        end
    end
    local function v36(v61)
        local v62 = 0
        local v63
        local v64
        while true do
            if (v62 == 3) then
                return v14(v64)
            end
            if (1 == v62) then
                v63 = v11(v27, v29, (v29 + v61) - 1)
                v29 = v29 + v61
                v62 = 2
            end
            if (v62 == 2) then
                v64 = {}
                for v112 = 1, #v63 do
                    v64[v112] = v10(v9(v11(v63, v112, v112)))
                end
                v62 = 3
            end
            if (0 == v62) then
                v63 = nil
                if not v61 then
                    v61 = v34()
                    if (v61 == 0) then
                        return ""
                    end
                end
                v62 = 1
            end
        end
    end
    local v37 = v34
    local function v38(...)
        return {...}, v20("#", ...)
    end
    local function v39()
        local v65 = {}
        local v66 = {}
        local v67 = {}
        local v68 = {v65, v66, nil, v67}
        local v69 = v34()
        local v70 = {}
        for v78 = 1, v69 do
            local v79 = 0
            local v80
            local v81
            while true do
                if (v79 == 0) then
                    v80 = v32()
                    v81 = nil
                    v79 = 1
                end
                if (v79 == 1) then
                    if (v80 == 1) then
                        v81 = v32() ~= 0
                    elseif (v80 == (2 - 0)) then
                        v81 = v35()
                    elseif (v80 == 3) then
                        v81 = v36()
                    end
                    v70[v78] = v81
                    break
                end
            end
        end
        v68[3] = v32()
        for v82 = 1, v34() do
            local v83 = 0
            local v84
            while true do
                if (v83 == 0) then
                    v84 = v32()
                    if (v31(v84, 1, 1) == 0) then
                        local v119 = 0
                        local v120
                        local v121
                        local v122
                        while true do
                            if (v119 == 0) then
                                v120 = v31(v84, 2, 3)
                                v121 = v31(v84, 4, 6)
                                v119 = 1
                            end
                            if (v119 == 1) then
                                v122 = {v33(), v33(), nil, nil}
                                if (v120 == 0) then
                                    v122[3] = v33()
                                    v122[4] = v33()
                                elseif (v120 == 1) then
                                    v122[3] = v34()
                                elseif (v120 == 2) then
                                    v122[1068 - (68 + 997)] = v34() - (2 ^ (1286 - (226 + 1044)))
                                elseif (v120 == 3) then
                                    local v330 = 0
                                    while true do
                                        if (v330 == 0) then
                                            v122[3] = v34() - (2 ^ 16)
                                            v122[4] = v33()
                                            break
                                        end
                                    end
                                end
                                v119 = 2
                            end
                            if (v119 == 2) then
                                if (v31(v121, 1, 1) == 1) then
                                    v122[2] = v70[v122[2]]
                                end
                                if (v31(v121, 2, 2) == 1) then
                                    v122[3] = v70[v122[3]]
                                end
                                v119 = 3
                            end
                            if (v119 == 3) then
                                if (v31(v121, 3, 3) == 1) then
                                    v122[4] = v70[v122[4]]
                                end
                                v65[v82] = v122
                                break
                            end
                        end
                    end
                    break
                end
            end
        end
        for v85 = 1, v34() do
            v66[v85 - (4 - 3)] = v39()
        end
        return v68
    end
    local function v40(v72, v73, v74)
        local v75 = v72[1]
        local v76 = v72[2]
        local v77 = v72[3]
        return function(...)
            local v87 = v75
            local v88 = v76
            local v89 = v77
            local v90 = v38
            local v91 = 1
            local v92 = -1
            local v93 = {}
            local v94 = {...}
            local v95 = v20("#", ...) - 1
            local v96 = {}
            local v97 = {}
            for v107 = 0, v95 do
                if (v107 >= v89) then
                    v93[v107 - v89] = v94[v107 + 1]
                else
                    v97[v107] = v94[v107 + 1]
                end
            end
            local v98 = (v95 - v89) + 1
            local v99
            local v100
            while true do
                v99 = v87[v91]
                v100 = v99[1]
                if (v100 <= 21) then
                    if (v100 <= (127 - (32 + 85))) then
                        if (v100 <= 4) then
                            if (v100 <= 1) then
                                if (v100 == 0) then
                                    v97[v99[2]] = v97[v99[3]] % v97[v99[4]]
                                else
                                    v97[v99[2]] = v74[v99[3]]
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v97[v99[2]] = v97[v99[3 + 0]][v99[4]]
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v97[v99[2]] = v74[v99[3]]
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v97[v99[2]] = v97[v99[3]][v99[4]]
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v97[v99[2]] = v74[v99[3]]
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v97[v99[2]] = v97[v99[1 + 2]][v99[4]]
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v97[v99[2]] = v74[v99[3]]
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    if not v97[v99[2]] then
                                        v91 = v91 + 1
                                    else
                                        v91 = v99[3]
                                    end
                                end
                            elseif (v100 <= (959 - (892 + 65))) then
                                if (v97[v99[2]] == v99[4]) then
                                    v91 = v91 + 1
                                else
                                    v91 = v99[3]
                                end
                            elseif (v100 > 3) then
                                local v190 = v99[2]
                                local v191 = v97[v190 + 2]
                                local v192 = v97[v190] + v191
                                v97[v190] = v192
                                if (v191 > (0 - 0)) then
                                    if (v192 <= v97[v190 + 1]) then
                                        local v384 = 0
                                        while true do
                                            if (v384 == 0) then
                                                v91 = v99[3]
                                                v97[v190 + (5 - 2)] = v192
                                                break
                                            end
                                        end
                                    end
                                elseif (v192 >= v97[v190 + 1]) then
                                    v91 = v99[3]
                                    v97[v190 + 3] = v192
                                end
                            else
                                v97[v99[2]] = v73[v99[3]]
                            end
                        elseif (v100 <= 7) then
                            if (v100 <= (8 - 3)) then
                                v97[v99[2]] = v99[3]
                            elseif (v100 > (356 - (87 + 263))) then
                                local v196 = v99[3]
                                local v197 = v97[v196]
                                for v277 = v196 + 1, v99[4] do
                                    v197 = v197 .. v97[v277]
                                end
                                v97[v99[2]] = v197
                            else
                                do
                                    return v97[v99[2]]()
                                end
                            end
                        elseif (v100 <= 8) then
                            v74[v99[3]] = v97[v99[2]]
                            v91 = v91 + 1
                            v99 = v87[v91]
                            v97[v99[182 - (67 + 113)]] = v74[v99[3]]
                            v91 = v91 + 1
                            v99 = v87[v91]
                            v97[v99[2]]()
                            v91 = v91 + 1
                            v99 = v87[v91]
                            v97[v99[2]] = v74[v99[3 + 0]]
                            v91 = v91 + 1
                            v99 = v87[v91]
                            v97[v99[2]]()
                            v91 = v91 + (2 - 1)
                            v99 = v87[v91]
                            v91 = v99[3]
                        elseif (v100 == (7 + 2)) then
                            local v199 = v99[2]
                            v97[v199](v97[v199 + 1])
                        else
                            v97[v99[2]] = {}
                        end
                    elseif (v100 <= 15) then
                        if (v100 <= 12) then
                            if (v100 == 11) then
                                local v147 = 0
                                local v148
                                local v149
                                local v150
                                local v151
                                local v152
                                while true do
                                    if (v147 == 1) then
                                        v97[v99[2]] = v73[v99[3]]
                                        v91 = v91 + 1
                                        v99 = v87[v91]
                                        v97[v99[2]] = v73[v99[3]]
                                        v147 = 2
                                    end
                                    if (v147 == 5) then
                                        v91 = v91 + (2 - 1)
                                        v99 = v87[v91]
                                        for v313 = v99[2], v99[3] do
                                            v97[v313] = nil
                                        end
                                        v91 = v91 + 1
                                        v147 = 6
                                    end
                                    if (6 == v147) then
                                        v99 = v87[v91]
                                        v152 = v99[2]
                                        v150, v151 = v90(v97[v152](v21(v97, v152 + 1, v99[3])))
                                        v92 = (v151 + v152) - 1
                                        v147 = 7
                                    end
                                    if (v147 == 7) then
                                        v149 = 0 - 0
                                        for v315 = v152, v92 do
                                            v149 = v149 + 1
                                            v97[v315] = v150[v149]
                                        end
                                        v91 = v91 + 1 + 0
                                        v99 = v87[v91]
                                        v147 = 8
                                    end
                                    if (v147 == 3) then
                                        v99 = v87[v91]
                                        v97[v99[2]] = {}
                                        v91 = v91 + (3 - 2)
                                        v99 = v87[v91]
                                        v147 = 4
                                    end
                                    if (v147 == 8) then
                                        v152 = v99[2]
                                        v148 = v97[v152]
                                        for v318 = v152 + 1, v92 do
                                            v15(v148, v97[v318])
                                        end
                                        break
                                    end
                                    if (v147 == 4) then
                                        v97[v99[2]] = v73[v99[3]]
                                        v91 = v91 + 1
                                        v99 = v87[v91]
                                        v97[v99[2]] = v97[v99[955 - (802 + 150)]]
                                        v147 = 5
                                    end
                                    if (v147 == 2) then
                                        v91 = v91 + 1
                                        v99 = v87[v91]
                                        v97[v99[2]] = v73[v99[3]]
                                        v91 = v91 + 1
                                        v147 = 3
                                    end
                                    if (0 == v147) then
                                        v148 = nil
                                        v149 = nil
                                        v150, v151 = nil
                                        v152 = nil
                                        v147 = 1
                                    end
                                end
                            else
                                v97[v99[2]] = v97[v99[3]] % v99[1001 - (915 + 82)]
                            end
                        elseif (v100 <= 13) then
                            for v174 = v99[2], v99[3] do
                                v97[v174] = nil
                            end
                        elseif (v100 > 14) then
                            local v201 = v99[2]
                            local v202, v203 = v90(v97[v201](v21(v97, v201 + 1, v92)))
                            v92 = (v203 + v201) - 1
                            local v204 = 0
                            for v296 = v201, v92 do
                                local v297 = 0
                                while true do
                                    if (v297 == 0) then
                                        v204 = v204 + 1
                                        v97[v296] = v202[v204]
                                        break
                                    end
                                end
                            end
                        else
                            local v205 = 0
                            local v206
                            local v207
                            while true do
                                if (v205 == 0) then
                                    v206 = v99[2]
                                    v207 = v97[v206]
                                    v205 = 1
                                end
                                if (v205 == 1) then
                                    for v389 = v206 + 1, v92 do
                                        v15(v207, v97[v389])
                                    end
                                    break
                                end
                            end
                        end
                    elseif (v100 <= (50 - 32)) then
                        if (v100 <= (10 + 6)) then
                            v97[v99[2]]()
                        elseif (v100 > 17) then
                            local v208 = 0
                            local v209
                            local v210
                            local v211
                            local v212
                            while true do
                                if (v208 == 0) then
                                    v209 = nil
                                    v210, v211 = nil
                                    v212 = nil
                                    v97[v99[2]] = v99[3]
                                    v208 = 1
                                end
                                if (v208 == 4) then
                                    v209 = 1187 - (1069 + 118)
                                    for v390 = v212, v92 do
                                        local v391 = 0
                                        while true do
                                            if (v391 == 0) then
                                                v209 = v209 + 1
                                                v97[v390] = v210[v209]
                                                break
                                            end
                                        end
                                    end
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v208 = 5
                                end
                                if (v208 == 5) then
                                    v212 = v99[2]
                                    v97[v212] = v97[v212](v21(v97, v212 + 1, v92))
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v208 = 6
                                end
                                if (v208 == 6) then
                                    if (v97[v99[2]] == v99[4]) then
                                        v91 = v91 + 1
                                    else
                                        v91 = v99[3]
                                    end
                                    break
                                end
                                if (v208 == 2) then
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v97[v99[2]] = v99[3]
                                    v91 = v91 + (1 - 0)
                                    v208 = 3
                                end
                                if (v208 == 1) then
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v212 = v99[2]
                                    v97[v212] = v97[v212](v21(v97, v212 + 1, v99[3]))
                                    v208 = 2
                                end
                                if (v208 == 3) then
                                    v99 = v87[v91]
                                    v212 = v99[2]
                                    v210, v211 = v90(v97[v212](v21(v97, v212 + 1, v99[3])))
                                    v92 = (v211 + v212) - 1
                                    v208 = 4
                                end
                            end
                        else
                            v91 = v99[3]
                        end
                    elseif (v100 <= 19) then
                        do
                            return
                        end
                    elseif (v100 == 20) then
                        local v214 = v99[2]
                        v97[v214] = v97[v214](v21(v97, v214 + 1, v92))
                    else
                        local v216 = 0
                        local v217
                        local v218
                        local v219
                        local v220
                        while true do
                            if (v216 == 1) then
                                v92 = (v219 + v217) - 1
                                v220 = 0
                                v216 = 2
                            end
                            if (v216 == 0) then
                                v217 = v99[2]
                                v218, v219 = v90(v97[v217](v97[v217 + 1]))
                                v216 = 1
                            end
                            if (2 == v216) then
                                for v392 = v217, v92 do
                                    local v393 = 0
                                    while true do
                                        if (v393 == 0) then
                                            v220 = v220 + (2 - 1)
                                            v97[v392] = v218[v220]
                                            break
                                        end
                                    end
                                end
                                break
                            end
                        end
                    end
                elseif (v100 <= (69 - 37)) then
                    if (v100 <= 26) then
                        if (v100 <= 23) then
                            if (v100 > (4 + 18)) then
                                local v154 = v99[2]
                                do
                                    return v97[v154](v21(v97, v154 + 1, v99[3]))
                                end
                            else
                                v97[v99[2]] = #v97[v99[3]]
                            end
                        elseif (v100 <= 24) then
                            v97[v99[2]] = v74[v99[3]]
                        elseif (v100 > 25) then
                            if not v97[v99[2]] then
                                v91 = v91 + 1
                            else
                                v91 = v99[3]
                            end
                        else
                            local v221 = 0
                            local v222
                            while true do
                                if (0 == v221) then
                                    v222 = v99[2]
                                    v97[v222] = v97[v222](v21(v97, v222 + (1 - 0), v99[3]))
                                    break
                                end
                            end
                        end
                    elseif (v100 <= 29) then
                        if (v100 <= 27) then
                            local v158 = v88[v99[3 + 0]]
                            local v159
                            local v160 = {}
                            v159 =
                                v18(
                                {},
                                {[v7("\17\148\66\201\83\169\54", "\204\78\203\43\167\55")] = function(v176, v177)
                                        local v178 = 0
                                        local v179
                                        while true do
                                            if (v178 == 0) then
                                                v179 = v160[v177]
                                                return v179[1][v179[2]]
                                            end
                                        end
                                    end, [v7("\110\154\164\38\9\181\95\161\175\59", "\220\49\197\202\67\126")] = function(
                                        v180,
                                        v181,
                                        v182)
                                        local v183 = 0
                                        local v184
                                        while true do
                                            if (v183 == 0) then
                                                v184 = v160[v181]
                                                v184[1][v184[2]] = v182
                                                break
                                            end
                                        end
                                    end}
                            )
                            for v185 = 1, v99[4] do
                                local v186 = 0
                                local v187
                                while true do
                                    if (v186 == 1) then
                                        if (v187[1] == 38) then
                                            v160[v185 - (792 - (368 + 423))] = {v97, v187[3]}
                                        else
                                            v160[v185 - (3 - 2)] = {v73, v187[3]}
                                        end
                                        v96[#v96 + 1] = v160
                                        break
                                    end
                                    if (0 == v186) then
                                        v91 = v91 + 1
                                        v187 = v87[v91]
                                        v186 = 1
                                    end
                                end
                            end
                            v97[v99[2]] = v40(v158, v159, v74)
                        elseif (v100 == 28) then
                            local v223 = 0
                            local v224
                            while true do
                                if (v223 == 0) then
                                    v224 = v99[2]
                                    do
                                        return v21(v97, v224, v92)
                                    end
                                    break
                                end
                            end
                        else
                            local v225 = 0
                            local v226
                            local v227
                            local v228
                            while true do
                                if (v225 == 1) then
                                    v91 = v91 + (19 - (10 + 8))
                                    v99 = v87[v91]
                                    v97[v99[2]] = v73[v99[11 - 8]]
                                    v91 = v91 + 1
                                    v225 = 2
                                end
                                if (v225 == 6) then
                                    for v396 = v227 + 1, v99[4] do
                                        v226 = v226 .. v97[v396]
                                    end
                                    v97[v99[2]] = v226
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v225 = 7
                                end
                                if (7 == v225) then
                                    v228 = v99[2]
                                    v97[v228](v97[v228 + 1])
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v225 = 8
                                end
                                if (v225 == 0) then
                                    v226 = nil
                                    v227 = nil
                                    v228 = nil
                                    v97[v99[2]] = v74[v99[3]]
                                    v225 = 1
                                end
                                if (v225 == 8) then
                                    v91 = v99[3]
                                    break
                                end
                                if (v225 == 3) then
                                    v97[v99[2]] = v99[3]
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v228 = v99[2]
                                    v225 = 4
                                end
                                if (5 == v225) then
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v227 = v99[3]
                                    v226 = v97[v227]
                                    v225 = 6
                                end
                                if (v225 == 2) then
                                    v99 = v87[v91]
                                    v97[v99[2]] = v99[3]
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v225 = 3
                                end
                                if (v225 == 4) then
                                    v97[v228] = v97[v228](v21(v97, v228 + 1, v99[3]))
                                    v91 = v91 + 1
                                    v99 = v87[v91]
                                    v97[v99[2]] = v97[v99[445 - (416 + 26)]]
                                    v225 = 5
                                end
                            end
                        end
                    elseif (v100 <= (95 - 65)) then
                        v97[v99[2]] = v97[v99[3]] + v99[4]
                    elseif (v100 > 31) then
                        local v229
                        local v230
                        local v231
                        v97[v99[2]] = {}
                        v91 = v91 + 1
                        v99 = v87[v91]
                        v97[v99[2]] = v99[3]
                        v91 = v91 + 1
                        v99 = v87[v91]
                        v97[v99[2]] = #v97[v99[3]]
                        v91 = v91 + 1
                        v99 = v87[v91]
                        v97[v99[1 + 1]] = v99[3]
                        v91 = v91 + 1
                        v99 = v87[v91]
                        v231 = v99[2]
                        v230 = v97[v231]
                        v229 = v97[v231 + 2]
                        if (v229 > (0 - 0)) then
                            if (v230 > v97[v231 + 1]) then
                                v91 = v99[3]
                            else
                                v97[v231 + 3] = v230
                            end
                        elseif (v230 < v97[v231 + 1]) then
                            v91 = v99[3]
                        else
                            v97[v231 + 3] = v230
                        end
                    elseif v97[v99[2]] then
                        v91 = v91 + 1
                    else
                        v91 = v99[3]
                    end
                elseif (v100 <= 37) then
                    if (v100 <= 34) then
                        if (v100 == 33) then
                            v97[v99[440 - (145 + 293)]] = v97[v99[3]] * v99[4]
                        else
                            local v164 = 0
                            local v165
                            while true do
                                if (0 == v164) then
                                    v165 = v99[2]
                                    v97[v165](v21(v97, v165 + 1, v92))
                                    break
                                end
                            end
                        end
                    elseif (v100 <= 35) then
                        local v166 = v99[432 - (44 + 386)]
                        local v167 = v97[v166]
                        local v168 = v97[v166 + 2]
                        if (v168 > 0) then
                            if (v167 > v97[v166 + 1]) then
                                v91 = v99[3]
                            else
                                v97[v166 + (1489 - (998 + 488))] = v167
                            end
                        elseif (v167 < v97[v166 + 1]) then
                            v91 = v99[3]
                        else
                            v97[v166 + 3] = v167
                        end
                    elseif (v100 == (12 + 24)) then
                        v74[v99[3]] = v97[v99[2]]
                    else
                        local v241 = v99[2]
                        local v242, v243 = v90(v97[v241](v21(v97, v241 + 1 + 0, v99[3])))
                        v92 = (v243 + v241) - 1
                        local v244 = 772 - (201 + 571)
                        for v299 = v241, v92 do
                            v244 = v244 + 1
                            v97[v299] = v242[v244]
                        end
                    end
                elseif (v100 <= 40) then
                    if (v100 <= (1176 - (116 + 1022))) then
                        v97[v99[2]] = v97[v99[12 - 9]]
                    elseif (v100 > 39) then
                        local v245 = 0
                        while true do
                            if (v245 == 3) then
                                v74[v99[3]] = v97[v99[2]]
                                break
                            end
                            if (1 == v245) then
                                v91 = v91 + 1 + 0
                                v99 = v87[v91]
                                v97[v99[7 - 5]]()
                                v91 = v91 + 1
                                v245 = 2
                            end
                            if (v245 == 2) then
                                v99 = v87[v91]
                                v97[v99[7 - 5]] = v99[3]
                                v91 = v91 + 1
                                v99 = v87[v91]
                                v245 = 3
                            end
                            if (0 == v245) then
                                v74[v99[3]] = v97[v99[2]]
                                v91 = v91 + 1
                                v99 = v87[v91]
                                v97[v99[2]] = v74[v99[3]]
                                v245 = 1
                            end
                        end
                    else
                        v97[v99[2]] = v99[3] + v97[v99[4]]
                    end
                elseif (v100 <= 41) then
                    v97[v99[2]] = v97[v99[3]][v99[4]]
                elseif (v100 > 42) then
                    local v247
                    local v248
                    local v249
                    v97[v99[2]] = v74[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[861 - (814 + 45)]] = v97[v99[7 - 4]] * v99[4]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v74[v99[3]] = v97[v99[2]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v74[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v73[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v99[1 + 2]
                    v91 = v91 + 1 + 0
                    v99 = v87[v91]
                    v97[v99[2]] = v99[3]
                    v91 = v91 + (886 - (261 + 624))
                    v99 = v87[v91]
                    v249 = v99[2]
                    v97[v249] = v97[v249](v21(v97, v249 + 1, v99[3]))
                    v91 = v91 + (1 - 0)
                    v99 = v87[v91]
                    v97[v99[2]] = v74[v99[3]]
                    v91 = v91 + (1081 - (1020 + 60))
                    v99 = v87[v91]
                    v248 = v99[3]
                    v247 = v97[v248]
                    for v302 = v248 + 1, v99[4] do
                        v247 = v247 .. v97[v302]
                    end
                    v97[v99[2]] = v247
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v249 = v99[2]
                    v97[v249](v97[v249 + 1])
                    v91 = v91 + (1424 - (630 + 793))
                    v99 = v87[v91]
                    do
                        return
                    end
                else
                    local v260
                    local v261, v262
                    local v263
                    v97[v99[2]] = v97[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v73[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[6 - 4]] = v73[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v73[v99[14 - 11]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v73[v99[2 + 1]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v97[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v97[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v97[v99[3]] + v99[4]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v263 = v99[2]
                    v261, v262 = v90(v97[v263](v21(v97, v263 + 1, v99[3])))
                    v92 = (v262 + v263) - 1
                    v260 = 0
                    for v303 = v263, v92 do
                        v260 = v260 + 1
                        v97[v303] = v261[v260]
                    end
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v263 = v99[6 - 4]
                    v97[v263] = v97[v263](v21(v97, v263 + 1, v92))
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v73[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v73[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v97[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = #v97[v99[3]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v97[v99[3]] % v97[v99[4]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v99[1750 - (760 + 987)] + v97[v99[4]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = #v97[v99[1916 - (1789 + 124)]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v97[v99[3]] % v97[v99[4]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v99[3] + v97[v99[4]]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v97[v99[3]] + v99[4]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v263 = v99[2]
                    v261, v262 = v90(v97[v263](v21(v97, v263 + 1, v99[3])))
                    v92 = (v262 + v263) - 1
                    v260 = 0
                    for v306 = v263, v92 do
                        v260 = v260 + (767 - (745 + 21))
                        v97[v306] = v261[v260]
                    end
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v263 = v99[2]
                    v261, v262 = v90(v97[v263](v21(v97, v263 + 1, v92)))
                    v92 = (v262 + v263) - 1
                    v260 = 0
                    for v309 = v263, v92 do
                        local v310 = 0
                        while true do
                            if (0 == v310) then
                                v260 = v260 + 1
                                v97[v309] = v261[v260]
                                break
                            end
                        end
                    end
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v263 = v99[2]
                    v97[v263] = v97[v263](v21(v97, v263 + 1, v92))
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v97[v99[2]] = v97[v99[2 + 1]] % v99[4]
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v263 = v99[5 - 3]
                    v261, v262 = v90(v97[v263](v97[v263 + 1]))
                    v92 = (v262 + v263) - 1
                    v260 = 0
                    for v311 = v263, v92 do
                        local v312 = 0
                        while true do
                            if (v312 == 0) then
                                v260 = v260 + 1
                                v97[v311] = v261[v260]
                                break
                            end
                        end
                    end
                    v91 = v91 + 1
                    v99 = v87[v91]
                    v263 = v99[7 - 5]
                    v97[v263](v21(v97, v263 + 1, v92))
                end
                v91 = v91 + 1
            end
        end
    end
    return v40(v39(), {}, v28)(...)
end
return v23(
    "LOL!0D3O0003063O00737472696E6703043O006368617203043O00627974652O033O0073756203053O0062697433322O033O0062697403043O0062786F7203053O007461626C6503063O00636F6E63617403063O00696E7365727403053O006D6174636803083O00746F6E756D62657203053O007063612O6C00243O0012013O00013O00206O000200122O000100013O00202O00010001000300122O000200013O00202O00020002000400122O000300053O00062O0003000A000100010004113O000A0001001218000300063O002029000400030007001218000500083O002029000500050009001218000600083O00202900060006000A00061B00073O000100062O00263O00064O00268O00263O00044O00263O00014O00263O00024O00263O00053O001218000800013O00202900080008000B0012180009000C3O001218000A000D3O00061B000B0001000100052O00263O00074O00263O00094O00263O00084O00263O000A4O00263O000B4O0026000C000B4O0006000C00014O001C000C6O00133O00013O00023O00023O00026O00F03F026O00704002264O002000025O00122O000300016O00045O00122O000500013O00042O0003002100012O000300076O002A000800026O000900016O000A00026O000B00036O000C00046O000D8O000E00063O00202O000F000600014O000C000F6O000B3O00024O000C00036O000D00046O000E00016O000F00016O000F0006000F00102O000F0001000F4O001000016O00100006001000102O00100001001000202O0010001000014O000D00106O000C8O000A3O000200202O000A000A00024O0009000A6O00073O0001002O040003000500012O0003000300054O0026000400024O0017000300044O001C00036O00133O00017O00043O00027O004003053O003A25642B3A2O033O0025642B026O00F03F001C3O00061B5O000100012O00038O000B000100016O000200026O000300026O00048O000500036O00068O000700076O000500076O00043O0001002029000400040001002O12000500026O00030005000200122O000400036O000200046O00013O000200262O00010018000100040004113O001800012O002600016O000A00026O0017000100024O001C00015O0004113O001B00012O0003000100044O0006000100014O001C00016O00133O00013O00013O00053O0003103O0063616C63756C61746550726F64756374030B3O0063616C63756C6174696F6E025O00C0724003113O0063616C63756C61746550726F6475637432026O00F03F01133O00061F3O001100013O0004113O0011000100061B00013O000100012O00037O001228000100013O00122O000100016O00010001000100122O000100033O00122O000100023O00061B00010001000100012O00037O001208000100043O00122O000100016O00010001000100122O000100046O00010001000100044O0012000100202900013O00052O00133O00013O00023O00063O00028O00026O00F03F025O0088E34003053O007072696E74031C3O007D1EB966A54C05A92AA30919BA66E51946FC6CF71B46EC66BE5A4CFC03053O00D72976DC4600193O0012053O00014O000D000100023O0026023O0007000100010004113O00070001001205000100014O000D000200023O0012053O00023O0026023O0002000100020004113O0002000100260200010009000100010004113O00090001001205000200033O00121D000300046O00045O00122O000500053O00122O000600066O0004000600024O000500026O0004000400054O00030002000100044O001800010004113O000900010004113O001800010004113O000200012O00133O00017O00063O00030B3O0063616C63756C6174696F6E025O00C0724003053O007072696E74031C3O00641E2752EC5505371EEA10192452AD00466258BE03467252F7434C6203053O009E3076427203063O00726573756C74000C3O00122B3O00013O00206O000200124O00013O00124O00036O00015O00122O000200043O00122O000300056O00010003000200122O000200066O0001000100026O000200016O00017O00",
    v17(),
    ...
)
