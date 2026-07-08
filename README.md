NoteDiscovery | Knowledge Base | Docker      NoteDiscovery: Base de conocimiento autohospedada en Docker (alternativa Obsidian...' property='og:description'/>
@font-face{font-family:'Damion';font-style:normal;font-weight:400;font-display:swap;src:url(//fonts.gstatic.com/s/damion/v15/hv-XlzJ3KEUe_YZkZGw2EzJwV9J-.woff2)format('woff2');unicode-range:U+0100-02BA,U+02BD-02C5,U+02C7-02CC,U+02CE-02D7,U+02DD-02FF,U+0304,U+0308,U+0329,U+1D00-1DBF,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20C0,U+2113,U+2C60-2C7F,U+A720-A7FF;}@font-face{font-family:'Damion';font-style:normal;font-weight:400;font-display:swap;src:url(//fonts.gstatic.com/s/damion/v15/hv-XlzJ3KEUe_YZkamw2EzJwVw.woff2)format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;}@font-face{font-family:'Playfair Display';font-style:normal;font-weight:900;font-display:swap;src:url(//fonts.gstatic.com/s/playfairdisplay/v40/nuFvD-vYSZviVYUb_rj3ij__anPXJzDwcbmjWBN2PKfsunDTbtPK-F2qC0usEw.woff2)format('woff2');unicode-range:U+0301,U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116;}@font-face{font-family:'Playfair Display';font-style:normal;font-weight:900;font-display:swap;src:url(//fonts.gstatic.com/s/playfairdisplay/v40/nuFvD-vYSZviVYUb_rj3ij__anPXJzDwcbmjWBN2PKfsunDYbtPK-F2qC0usEw.woff2)format('woff2');unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+0300-0301,U+0303-0304,U+0308-0309,U+0323,U+0329,U+1EA0-1EF9,U+20AB;}@font-face{font-family:'Playfair Display';font-style:normal;font-weight:900;font-display:swap;src:url(//fonts.gstatic.com/s/playfairdisplay/v40/nuFvD-vYSZviVYUb_rj3ij__anPXJzDwcbmjWBN2PKfsunDZbtPK-F2qC0usEw.woff2)format('woff2');unicode-range:U+0100-02BA,U+02BD-02C5,U+02C7-02CC,U+02CE-02D7,U+02DD-02FF,U+0304,U+0308,U+0329,U+1D00-1DBF,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20C0,U+2113,U+2C60-2C7F,U+A720-A7FF;}@font-face{font-family:'Playfair Display';font-style:normal;font-weight:900;font-display:swap;src:url(//fonts.gstatic.com/s/playfairdisplay/v40/nuFvD-vYSZviVYUb_rj3ij__anPXJzDwcbmjWBN2PKfsunDXbtPK-F2qC0s.woff2)format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;}@font-face{font-family:'Roboto';font-style:italic;font-weight:300;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFOKCnqEu92Fr1Mu53ZEC9_Vu3r1gIhOszmOClHrs6ljXfMMLt_QuAX-k3Yi128m0kN2.woff2)format('woff2');unicode-range:U+0460-052F,U+1C80-1C8A,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F;}@font-face{font-family:'Roboto';font-style:italic;font-weight:300;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFOKCnqEu92Fr1Mu53ZEC9_Vu3r1gIhOszmOClHrs6ljXfMMLt_QuAz-k3Yi128m0kN2.woff2)format('woff2');unicode-range:U+0301,U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116;}@font-face{font-family:'Roboto';font-style:italic;font-weight:300;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFOKCnqEu92Fr1Mu53ZEC9_Vu3r1gIhOszmOClHrs6ljXfMMLt_QuAT-k3Yi128m0kN2.woff2)format('woff2');unicode-range:U+1F00-1FFF;}@font-face{font-family:'Roboto';font-style:italic;font-weight:300;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFOKCnqEu92Fr1Mu53ZEC9_Vu3r1gIhOszmOClHrs6ljXfMMLt_QuAv-k3Yi128m0kN2.woff2)format('woff2');unicode-range:U+0370-0377,U+037A-037F,U+0384-038A,U+038C,U+038E-03A1,U+03A3-03FF;}@font-face{font-family:'Roboto';font-style:italic;font-weight:300;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFOKCnqEu92Fr1Mu53ZEC9_Vu3r1gIhOszmOClHrs6ljXfMMLt_QuHT-k3Yi128m0kN2.woff2)format('woff2');unicode-range:U+0302-0303,U+0305,U+0307-0308,U+0310,U+0312,U+0315,U+031A,U+0326-0327,U+032C,U+032F-0330,U+0332-0333,U+0338,U+033A,U+0346,U+034D,U+0391-03A1,U+03A3-03A9,U+03B1-03C9,U+03D1,U+03D5-03D6,U+03F0-03F1,U+03F4-03F5,U+2016-2017,U+2034-2038,U+203C,U+2040,U+2043,U+2047,U+2050,U+2057,U+205F,U+2070-2071,U+2074-208E,U+2090-209C,U+20D0-20DC,U+20E1,U+20E5-20EF,U+2100-2112,U+2114-2115,U+2117-2121,U+2123-214F,U+2190,U+2192,U+2194-21AE,U+21B0-21E5,U+21F1-21F2,U+21F4-2211,U+2213-2214,U+2216-22FF,U+2308-230B,U+2310,U+2319,U+231C-2321,U+2336-237A,U+237C,U+2395,U+239B-23B7,U+23D0,U+23DC-23E1,U+2474-2475,U+25AF,U+25B3,U+25B7,U+25BD,U+25C1,U+25CA,U+25CC,U+25FB,U+266D-266F,U+27C0-27FF,U+2900-2AFF,U+2B0E-2B11,U+2B30-2B4C,U+2BFE,U+3030,U+FF5B,U+FF5D,U+1D400-1D7FF,U+1EE00-1EEFF;}@font-face{font-family:'Roboto';font-style:italic;font-weight:300;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFOKCnqEu92Fr1Mu53ZEC9_Vu3r1gIhOszmOClHrs6ljXfMMLt_QuGb-k3Yi128m0kN2.woff2)format('woff2');unicode-range:U+0001-000C,U+000E-001F,U+007F-009F,U+20DD-20E0,U+20E2-20E4,U+2150-218F,U+2190,U+2192,U+2194-2199,U+21AF,U+21E6-21F0,U+21F3,U+2218-2219,U+2299,U+22C4-22C6,U+2300-243F,U+2440-244A,U+2460-24FF,U+25A0-27BF,U+2800-28FF,U+2921-2922,U+2981,U+29BF,U+29EB,U+2B00-2BFF,U+4DC0-4DFF,U+FFF9-FFFB,U+10140-1018E,U+10190-1019C,U+101A0,U+101D0-101FD,U+102E0-102FB,U+10E60-10E7E,U+1D2C0-1D2D3,U+1D2E0-1D37F,U+1F000-1F0FF,U+1F100-1F1AD,U+1F1E6-1F1FF,U+1F30D-1F30F,U+1F315,U+1F31C,U+1F31E,U+1F320-1F32C,U+1F336,U+1F378,U+1F37D,U+1F382,U+1F393-1F39F,U+1F3A7-1F3A8,U+1F3AC-1F3AF,U+1F3C2,U+1F3C4-1F3C6,U+1F3CA-1F3CE,U+1F3D4-1F3E0,U+1F3ED,U+1F3F1-1F3F3,U+1F3F5-1F3F7,U+1F408,U+1F415,U+1F41F,U+1F426,U+1F43F,U+1F441-1F442,U+1F444,U+1F446-1F449,U+1F44C-1F44E,U+1F453,U+1F46A,U+1F47D,U+1F4A3,U+1F4B0,U+1F4B3,U+1F4B9,U+1F4BB,U+1F4BF,U+1F4C8-1F4CB,U+1F4D6,U+1F4DA,U+1F4DF,U+1F4E3-1F4E6,U+1F4EA-1F4ED,U+1F4F7,U+1F4F9-1F4FB,U+1F4FD-1F4FE,U+1F503,U+1F507-1F50B,U+1F50D,U+1F512-1F513,U+1F53E-1F54A,U+1F54F-1F5FA,U+1F610,U+1F650-1F67F,U+1F687,U+1F68D,U+1F691,U+1F694,U+1F698,U+1F6AD,U+1F6B2,U+1F6B9-1F6BA,U+1F6BC,U+1F6C6-1F6CF,U+1F6D3-1F6D7,U+1F6E0-1F6EA,U+1F6F0-1F6F3,U+1F6F7-1F6FC,U+1F700-1F7FF,U+1F800-1F80B,U+1F810-1F847,U+1F850-1F859,U+1F860-1F887,U+1F890-1F8AD,U+1F8B0-1F8BB,U+1F8C0-1F8C1,U+1F900-1F90B,U+1F93B,U+1F946,U+1F984,U+1F996,U+1F9E9,U+1FA00-1FA6F,U+1FA70-1FA7C,U+1FA80-1FA89,U+1FA8F-1FAC6,U+1FACE-1FADC,U+1FADF-1FAE9,U+1FAF0-1FAF8,U+1FB00-1FBFF;}@font-face{font-family:'Roboto';font-style:italic;font-weight:300;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFOKCnqEu92Fr1Mu53ZEC9_Vu3r1gIhOszmOClHrs6ljXfMMLt_QuAf-k3Yi128m0kN2.woff2)format('woff2');unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+0300-0301,U+0303-0304,U+0308-0309,U+0323,U+0329,U+1EA0-1EF9,U+20AB;}@font-face{font-family:'Roboto';font-style:italic;font-weight:300;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFOKCnqEu92Fr1Mu53ZEC9_Vu3r1gIhOszmOClHrs6ljXfMMLt_QuAb-k3Yi128m0kN2.woff2)format('woff2');unicode-range:U+0100-02BA,U+02BD-02C5,U+02C7-02CC,U+02CE-02D7,U+02DD-02FF,U+0304,U+0308,U+0329,U+1D00-1DBF,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20C0,U+2113,U+2C60-2C7F,U+A720-A7FF;}@font-face{font-family:'Roboto';font-style:italic;font-weight:300;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFOKCnqEu92Fr1Mu53ZEC9_Vu3r1gIhOszmOClHrs6ljXfMMLt_QuAj-k3Yi128m0g.woff2)format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;}@font-face{font-family:'Roboto';font-style:normal;font-weight:400;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3GUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0460-052F,U+1C80-1C8A,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F;}@font-face{font-family:'Roboto';font-style:normal;font-weight:400;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3iUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0301,U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116;}@font-face{font-family:'Roboto';font-style:normal;font-weight:400;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3CUBHMdazTgWw.woff2)format('woff2');unicode-range:U+1F00-1FFF;}@font-face{font-family:'Roboto';font-style:normal;font-weight:400;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3-UBHMdazTgWw.woff2)format('woff2');unicode-range:U+0370-0377,U+037A-037F,U+0384-038A,U+038C,U+038E-03A1,U+03A3-03FF;}@font-face{font-family:'Roboto';font-style:normal;font-weight:400;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMawCUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0302-0303,U+0305,U+0307-0308,U+0310,U+0312,U+0315,U+031A,U+0326-0327,U+032C,U+032F-0330,U+0332-0333,U+0338,U+033A,U+0346,U+034D,U+0391-03A1,U+03A3-03A9,U+03B1-03C9,U+03D1,U+03D5-03D6,U+03F0-03F1,U+03F4-03F5,U+2016-2017,U+2034-2038,U+203C,U+2040,U+2043,U+2047,U+2050,U+2057,U+205F,U+2070-2071,U+2074-208E,U+2090-209C,U+20D0-20DC,U+20E1,U+20E5-20EF,U+2100-2112,U+2114-2115,U+2117-2121,U+2123-214F,U+2190,U+2192,U+2194-21AE,U+21B0-21E5,U+21F1-21F2,U+21F4-2211,U+2213-2214,U+2216-22FF,U+2308-230B,U+2310,U+2319,U+231C-2321,U+2336-237A,U+237C,U+2395,U+239B-23B7,U+23D0,U+23DC-23E1,U+2474-2475,U+25AF,U+25B3,U+25B7,U+25BD,U+25C1,U+25CA,U+25CC,U+25FB,U+266D-266F,U+27C0-27FF,U+2900-2AFF,U+2B0E-2B11,U+2B30-2B4C,U+2BFE,U+3030,U+FF5B,U+FF5D,U+1D400-1D7FF,U+1EE00-1EEFF;}@font-face{font-family:'Roboto';font-style:normal;font-weight:400;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMaxKUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0001-000C,U+000E-001F,U+007F-009F,U+20DD-20E0,U+20E2-20E4,U+2150-218F,U+2190,U+2192,U+2194-2199,U+21AF,U+21E6-21F0,U+21F3,U+2218-2219,U+2299,U+22C4-22C6,U+2300-243F,U+2440-244A,U+2460-24FF,U+25A0-27BF,U+2800-28FF,U+2921-2922,U+2981,U+29BF,U+29EB,U+2B00-2BFF,U+4DC0-4DFF,U+FFF9-FFFB,U+10140-1018E,U+10190-1019C,U+101A0,U+101D0-101FD,U+102E0-102FB,U+10E60-10E7E,U+1D2C0-1D2D3,U+1D2E0-1D37F,U+1F000-1F0FF,U+1F100-1F1AD,U+1F1E6-1F1FF,U+1F30D-1F30F,U+1F315,U+1F31C,U+1F31E,U+1F320-1F32C,U+1F336,U+1F378,U+1F37D,U+1F382,U+1F393-1F39F,U+1F3A7-1F3A8,U+1F3AC-1F3AF,U+1F3C2,U+1F3C4-1F3C6,U+1F3CA-1F3CE,U+1F3D4-1F3E0,U+1F3ED,U+1F3F1-1F3F3,U+1F3F5-1F3F7,U+1F408,U+1F415,U+1F41F,U+1F426,U+1F43F,U+1F441-1F442,U+1F444,U+1F446-1F449,U+1F44C-1F44E,U+1F453,U+1F46A,U+1F47D,U+1F4A3,U+1F4B0,U+1F4B3,U+1F4B9,U+1F4BB,U+1F4BF,U+1F4C8-1F4CB,U+1F4D6,U+1F4DA,U+1F4DF,U+1F4E3-1F4E6,U+1F4EA-1F4ED,U+1F4F7,U+1F4F9-1F4FB,U+1F4FD-1F4FE,U+1F503,U+1F507-1F50B,U+1F50D,U+1F512-1F513,U+1F53E-1F54A,U+1F54F-1F5FA,U+1F610,U+1F650-1F67F,U+1F687,U+1F68D,U+1F691,U+1F694,U+1F698,U+1F6AD,U+1F6B2,U+1F6B9-1F6BA,U+1F6BC,U+1F6C6-1F6CF,U+1F6D3-1F6D7,U+1F6E0-1F6EA,U+1F6F0-1F6F3,U+1F6F7-1F6FC,U+1F700-1F7FF,U+1F800-1F80B,U+1F810-1F847,U+1F850-1F859,U+1F860-1F887,U+1F890-1F8AD,U+1F8B0-1F8BB,U+1F8C0-1F8C1,U+1F900-1F90B,U+1F93B,U+1F946,U+1F984,U+1F996,U+1F9E9,U+1FA00-1FA6F,U+1FA70-1FA7C,U+1FA80-1FA89,U+1FA8F-1FAC6,U+1FACE-1FADC,U+1FADF-1FAE9,U+1FAF0-1FAF8,U+1FB00-1FBFF;}@font-face{font-family:'Roboto';font-style:normal;font-weight:400;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3OUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+0300-0301,U+0303-0304,U+0308-0309,U+0323,U+0329,U+1EA0-1EF9,U+20AB;}@font-face{font-family:'Roboto';font-style:normal;font-weight:400;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3KUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0100-02BA,U+02BD-02C5,U+02C7-02CC,U+02CE-02D7,U+02DD-02FF,U+0304,U+0308,U+0329,U+1D00-1DBF,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20C0,U+2113,U+2C60-2C7F,U+A720-A7FF;}@font-face{font-family:'Roboto';font-style:normal;font-weight:400;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3yUBHMdazQ.woff2)format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;}@font-face{font-family:'Roboto';font-style:normal;font-weight:700;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3GUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0460-052F,U+1C80-1C8A,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F;}@font-face{font-family:'Roboto';font-style:normal;font-weight:700;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3iUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0301,U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116;}@font-face{font-family:'Roboto';font-style:normal;font-weight:700;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3CUBHMdazTgWw.woff2)format('woff2');unicode-range:U+1F00-1FFF;}@font-face{font-family:'Roboto';font-style:normal;font-weight:700;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3-UBHMdazTgWw.woff2)format('woff2');unicode-range:U+0370-0377,U+037A-037F,U+0384-038A,U+038C,U+038E-03A1,U+03A3-03FF;}@font-face{font-family:'Roboto';font-style:normal;font-weight:700;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMawCUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0302-0303,U+0305,U+0307-0308,U+0310,U+0312,U+0315,U+031A,U+0326-0327,U+032C,U+032F-0330,U+0332-0333,U+0338,U+033A,U+0346,U+034D,U+0391-03A1,U+03A3-03A9,U+03B1-03C9,U+03D1,U+03D5-03D6,U+03F0-03F1,U+03F4-03F5,U+2016-2017,U+2034-2038,U+203C,U+2040,U+2043,U+2047,U+2050,U+2057,U+205F,U+2070-2071,U+2074-208E,U+2090-209C,U+20D0-20DC,U+20E1,U+20E5-20EF,U+2100-2112,U+2114-2115,U+2117-2121,U+2123-214F,U+2190,U+2192,U+2194-21AE,U+21B0-21E5,U+21F1-21F2,U+21F4-2211,U+2213-2214,U+2216-22FF,U+2308-230B,U+2310,U+2319,U+231C-2321,U+2336-237A,U+237C,U+2395,U+239B-23B7,U+23D0,U+23DC-23E1,U+2474-2475,U+25AF,U+25B3,U+25B7,U+25BD,U+25C1,U+25CA,U+25CC,U+25FB,U+266D-266F,U+27C0-27FF,U+2900-2AFF,U+2B0E-2B11,U+2B30-2B4C,U+2BFE,U+3030,U+FF5B,U+FF5D,U+1D400-1D7FF,U+1EE00-1EEFF;}@font-face{font-family:'Roboto';font-style:normal;font-weight:700;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMaxKUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0001-000C,U+000E-001F,U+007F-009F,U+20DD-20E0,U+20E2-20E4,U+2150-218F,U+2190,U+2192,U+2194-2199,U+21AF,U+21E6-21F0,U+21F3,U+2218-2219,U+2299,U+22C4-22C6,U+2300-243F,U+2440-244A,U+2460-24FF,U+25A0-27BF,U+2800-28FF,U+2921-2922,U+2981,U+29BF,U+29EB,U+2B00-2BFF,U+4DC0-4DFF,U+FFF9-FFFB,U+10140-1018E,U+10190-1019C,U+101A0,U+101D0-101FD,U+102E0-102FB,U+10E60-10E7E,U+1D2C0-1D2D3,U+1D2E0-1D37F,U+1F000-1F0FF,U+1F100-1F1AD,U+1F1E6-1F1FF,U+1F30D-1F30F,U+1F315,U+1F31C,U+1F31E,U+1F320-1F32C,U+1F336,U+1F378,U+1F37D,U+1F382,U+1F393-1F39F,U+1F3A7-1F3A8,U+1F3AC-1F3AF,U+1F3C2,U+1F3C4-1F3C6,U+1F3CA-1F3CE,U+1F3D4-1F3E0,U+1F3ED,U+1F3F1-1F3F3,U+1F3F5-1F3F7,U+1F408,U+1F415,U+1F41F,U+1F426,U+1F43F,U+1F441-1F442,U+1F444,U+1F446-1F449,U+1F44C-1F44E,U+1F453,U+1F46A,U+1F47D,U+1F4A3,U+1F4B0,U+1F4B3,U+1F4B9,U+1F4BB,U+1F4BF,U+1F4C8-1F4CB,U+1F4D6,U+1F4DA,U+1F4DF,U+1F4E3-1F4E6,U+1F4EA-1F4ED,U+1F4F7,U+1F4F9-1F4FB,U+1F4FD-1F4FE,U+1F503,U+1F507-1F50B,U+1F50D,U+1F512-1F513,U+1F53E-1F54A,U+1F54F-1F5FA,U+1F610,U+1F650-1F67F,U+1F687,U+1F68D,U+1F691,U+1F694,U+1F698,U+1F6AD,U+1F6B2,U+1F6B9-1F6BA,U+1F6BC,U+1F6C6-1F6CF,U+1F6D3-1F6D7,U+1F6E0-1F6EA,U+1F6F0-1F6F3,U+1F6F7-1F6FC,U+1F700-1F7FF,U+1F800-1F80B,U+1F810-1F847,U+1F850-1F859,U+1F860-1F887,U+1F890-1F8AD,U+1F8B0-1F8BB,U+1F8C0-1F8C1,U+1F900-1F90B,U+1F93B,U+1F946,U+1F984,U+1F996,U+1F9E9,U+1FA00-1FA6F,U+1FA70-1FA7C,U+1FA80-1FA89,U+1FA8F-1FAC6,U+1FACE-1FADC,U+1FADF-1FAE9,U+1FAF0-1FAF8,U+1FB00-1FBFF;}@font-face{font-family:'Roboto';font-style:normal;font-weight:700;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3OUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+0300-0301,U+0303-0304,U+0308-0309,U+0323,U+0329,U+1EA0-1EF9,U+20AB;}@font-face{font-family:'Roboto';font-style:normal;font-weight:700;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3KUBHMdazTgWw.woff2)format('woff2');unicode-range:U+0100-02BA,U+02BD-02C5,U+02C7-02CC,U+02CE-02D7,U+02DD-02FF,U+0304,U+0308,U+0329,U+1D00-1DBF,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20C0,U+2113,U+2C60-2C7F,U+A720-A7FF;}@font-face{font-family:'Roboto';font-style:normal;font-weight:700;font-stretch:100%;font-display:swap;src:url(//fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3yUBHMdazQ.woff2)format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;}
<!--
/*! normalize.css v3.0.1 | MIT License | git.io/normalize */html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}body{margin:0}article,aside,details,figcaption,figure,footer,header,hgroup,main,nav,section,summary{display:block}audio,canvas,progress,video{display:inline-block;vertical-align:baseline}audio:not([controls]){display:none;height:0}[hidden],template{display:none}a{background:transparent}a:active,a:hover{outline:0}abbr[title]{border-bottom:1px dotted}b,strong{font-weight:bold}dfn{font-style:italic}h1{font-size:2em;margin:.67em 0}mark{background:#ff0;color:#000}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-0.5em}sub{bottom:-0.25em}img{border:0}svg:not(:root){overflow:hidden}figure{margin:1em 40px}hr{-moz-box-sizing:content-box;box-sizing:content-box;height:0}pre{overflow:auto}code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}button,input,optgroup,select,textarea{color:inherit;font:inherit;margin:0}button{overflow:visible}button,select{text-transform:none}button,html input[type="button"],input[type="reset"],input[type="submit"]{-webkit-appearance:button;cursor:pointer}button[disabled],html input[disabled]{cursor:default}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}input{line-height:normal}input[type="checkbox"],input[type="radio"]{box-sizing:border-box;padding:0}input[type="number"]::-webkit-inner-spin-button,input[type="number"]::-webkit-outer-spin-button{height:auto}input[type="search"]{-webkit-appearance:textfield;-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box}input[type="search"]::-webkit-search-cancel-button,input[type="search"]::-webkit-search-decoration{-webkit-appearance:none}fieldset{border:1px solid #c0c0c0;margin:0 2px;padding:.35em .625em .75em}legend{border:0;padding:0}textarea{overflow:auto}optgroup{font-weight:bold}table{border-collapse:collapse;border-spacing:0}td,th{padding:0}
/*!************************************************
* Blogger Template Style
* Name: Contempo
**************************************************/
body{
overflow-wrap:break-word;
word-break:break-word;
word-wrap:break-word
}
.hidden{
display:none
}
.invisible{
visibility:hidden
}
.container::after,.float-container::after{
clear:both;
content:"";
display:table
}
.clearboth{
clear:both
}
#comments .comment .comment-actions,.subscribe-popup .FollowByEmail .follow-by-email-submit,.widget.Profile .profile-link,.widget.Profile .profile-link.visit-profile{
background:0 0;
border:0;
box-shadow:none;
color:#2196f3;
cursor:pointer;
font-size:14px;
font-weight:700;
outline:0;
text-decoration:none;
text-transform:uppercase;
width:auto
}
.dim-overlay{
background-color:rgba(0,0,0,.54);
height:100vh;
left:0;
position:fixed;
top:0;
width:100%
}
#sharing-dim-overlay{
background-color:transparent
}
input::-ms-clear{
display:none
}
.blogger-logo,.svg-icon-24.blogger-logo{
fill:#ff9800;
opacity:1
}
.loading-spinner-large{
-webkit-animation:mspin-rotate 1.568s infinite linear;
animation:mspin-rotate 1.568s infinite linear;
height:48px;
overflow:hidden;
position:absolute;
width:48px;
z-index:200
}
.loading-spinner-large>div{
-webkit-animation:mspin-revrot 5332ms infinite steps(4);
animation:mspin-revrot 5332ms infinite steps(4)
}
.loading-spinner-large>div>div{
-webkit-animation:mspin-singlecolor-large-film 1333ms infinite steps(81);
animation:mspin-singlecolor-large-film 1333ms infinite steps(81);
background-size:100%;
height:48px;
width:3888px
}
.mspin-black-large>div>div,.mspin-grey_54-large>div>div{
background-image:url(https://www.blogblog.com/indie/mspin_black_large.svg)
}
.mspin-white-large>div>div{
background-image:url(https://www.blogblog.com/indie/mspin_white_large.svg)
}
.mspin-grey_54-large{
opacity:.54
}
@-webkit-keyframes mspin-singlecolor-large-film{
from{
-webkit-transform:translateX(0);
transform:translateX(0)
}
to{
-webkit-transform:translateX(-3888px);
transform:translateX(-3888px)
}
}
@keyframes mspin-singlecolor-large-film{
from{
-webkit-transform:translateX(0);
transform:translateX(0)
}
to{
-webkit-transform:translateX(-3888px);
transform:translateX(-3888px)
}
}
@-webkit-keyframes mspin-rotate{
from{
-webkit-transform:rotate(0);
transform:rotate(0)
}
to{
-webkit-transform:rotate(360deg);
transform:rotate(360deg)
}
}
@keyframes mspin-rotate{
from{
-webkit-transform:rotate(0);
transform:rotate(0)
}
to{
-webkit-transform:rotate(360deg);
transform:rotate(360deg)
}
}
@-webkit-keyframes mspin-revrot{
from{
-webkit-transform:rotate(0);
transform:rotate(0)
}
to{
-webkit-transform:rotate(-360deg);
transform:rotate(-360deg)
}
}
@keyframes mspin-revrot{
from{
-webkit-transform:rotate(0);
transform:rotate(0)
}
to{
-webkit-transform:rotate(-360deg);
transform:rotate(-360deg)
}
}
.skip-navigation{
background-color:#fff;
box-sizing:border-box;
color:#000;
display:block;
height:0;
left:0;
line-height:50px;
overflow:hidden;
padding-top:0;
position:fixed;
text-align:center;
top:0;
-webkit-transition:box-shadow .3s,height .3s,padding-top .3s;
transition:box-shadow .3s,height .3s,padding-top .3s;
width:100%;
z-index:900
}
.skip-navigation:focus{
box-shadow:0 4px 5px 0 rgba(0,0,0,.14),0 1px 10px 0 rgba(0,0,0,.12),0 2px 4px -1px rgba(0,0,0,.2);
height:50px
}
#main{
outline:0
}
.main-heading{
position:absolute;
clip:rect(1px,1px,1px,1px);
padding:0;
border:0;
height:1px;
width:1px;
overflow:hidden
}
.Attribution{
margin-top:1em;
text-align:center
}
.Attribution .blogger img,.Attribution .blogger svg{
vertical-align:bottom
}
.Attribution .blogger img{
margin-right:.5em
}
.Attribution div{
line-height:24px;
margin-top:.5em
}
.Attribution .copyright,.Attribution .image-attribution{
font-size:.7em;
margin-top:1.5em
}
.BLOG_mobile_video_class{
display:none
}
.bg-photo{
background-attachment:scroll!important
}
body .CSS_LIGHTBOX{
z-index:900
}
.extendable .show-less,.extendable .show-more{
border-color:#2196f3;
color:#2196f3;
margin-top:8px
}
.extendable .show-less.hidden,.extendable .show-more.hidden{
display:none
}
.inline-ad{
display:none;
max-width:100%;
overflow:hidden
}
.adsbygoogle{
display:block
}
#cookieChoiceInfo{
bottom:0;
top:auto
}
iframe.b-hbp-video{
border:0
}
.post-body img{
max-width:100%
}
.post-body iframe{
max-width:100%
}
.post-body a[imageanchor="1"]{
display:inline-block
}
.byline{
margin-right:1em
}
.byline:last-child{
margin-right:0
}
.link-copied-dialog{
max-width:520px;
outline:0
}
.link-copied-dialog .modal-dialog-buttons{
margin-top:8px
}
.link-copied-dialog .goog-buttonset-default{
background:0 0;
border:0
}
.link-copied-dialog .goog-buttonset-default:focus{
outline:0
}
.paging-control-container{
margin-bottom:16px
}
.paging-control-container .paging-control{
display:inline-block
}
.paging-control-container .comment-range-text::after,.paging-control-container .paging-control{
color:#2196f3
}
.paging-control-container .comment-range-text,.paging-control-container .paging-control{
margin-right:8px
}
.paging-control-container .comment-range-text::after,.paging-control-container .paging-control::after{
content:"\b7";
cursor:default;
padding-left:8px;
pointer-events:none
}
.paging-control-container .comment-range-text:last-child::after,.paging-control-container .paging-control:last-child::after{
content:none
}
.byline.reactions iframe{
height:20px
}
.b-notification{
color:#000;
background-color:#fff;
border-bottom:solid 1px #000;
box-sizing:border-box;
padding:16px 32px;
text-align:center
}
.b-notification.visible{
-webkit-transition:margin-top .3s cubic-bezier(.4,0,.2,1);
transition:margin-top .3s cubic-bezier(.4,0,.2,1)
}
.b-notification.invisible{
position:absolute
}
.b-notification-close{
position:absolute;
right:8px;
top:8px
}
.no-posts-message{
line-height:40px;
text-align:center
}
@media screen and (max-width:800px){
body.item-view .post-body a[imageanchor="1"][style*="float: left;"],body.item-view .post-body a[imageanchor="1"][style*="float: right;"]{
float:none!important;
clear:none!important
}
body.item-view .post-body a[imageanchor="1"] img{
display:block;
height:auto;
margin:0 auto
}
body.item-view .post-body>.separator:first-child>a[imageanchor="1"]:first-child{
margin-top:20px
}
.post-body a[imageanchor]{
display:block
}
body.item-view .post-body a[imageanchor="1"]{
margin-left:0!important;
margin-right:0!important
}
body.item-view .post-body a[imageanchor="1"]+a[imageanchor="1"]{
margin-top:16px
}
}
.item-control{
display:none
}
#comments{
border-top:1px dashed rgba(0,0,0,.54);
margin-top:20px;
padding:20px
}
#comments .comment-thread ol{
margin:0;
padding-left:0;
padding-left:0
}
#comments .comment .comment-replybox-single,#comments .comment-thread .comment-replies{
margin-left:60px
}
#comments .comment-thread .thread-count{
display:none
}
#comments .comment{
list-style-type:none;
padding:0 0 30px;
position:relative
}
#comments .comment .comment{
padding-bottom:8px
}
.comment .avatar-image-container{
position:absolute
}
.comment .avatar-image-container img{
border-radius:50%
}
.avatar-image-container svg,.comment .avatar-image-container .avatar-icon{
border-radius:50%;
border:solid 1px #707070;
box-sizing:border-box;
fill:#707070;
height:35px;
margin:0;
padding:7px;
width:35px
}
.comment .comment-block{
margin-top:10px;
margin-left:60px;
padding-bottom:0
}
#comments .comment-author-header-wrapper{
margin-left:40px
}
#comments .comment .thread-expanded .comment-block{
padding-bottom:20px
}
#comments .comment .comment-header .user,#comments .comment .comment-header .user a{
color:#212121;
font-style:normal;
font-weight:700
}
#comments .comment .comment-actions{
bottom:0;
margin-bottom:15px;
position:absolute
}
#comments .comment .comment-actions>*{
margin-right:8px
}
#comments .comment .comment-header .datetime{
bottom:0;
color:rgba(33,33,33,.54);
display:inline-block;
font-size:13px;
font-style:italic;
margin-left:8px
}
#comments .comment .comment-footer .comment-timestamp a,#comments .comment .comment-header .datetime a{
color:rgba(33,33,33,.54)
}
#comments .comment .comment-content,.comment .comment-body{
margin-top:12px;
word-break:break-word
}
.comment-body{
margin-bottom:12px
}
#comments.embed[data-num-comments="0"]{
border:0;
margin-top:0;
padding-top:0
}
#comments.embed[data-num-comments="0"] #comment-post-message,#comments.embed[data-num-comments="0"] div.comment-form>p,#comments.embed[data-num-comments="0"] p.comment-footer{
display:none
}
#comment-editor-src{
display:none
}
.comments .comments-content .loadmore.loaded{
max-height:0;
opacity:0;
overflow:hidden
}
.extendable .remaining-items{
height:0;
overflow:hidden;
-webkit-transition:height .3s cubic-bezier(.4,0,.2,1);
transition:height .3s cubic-bezier(.4,0,.2,1)
}
.extendable .remaining-items.expanded{
height:auto
}
.svg-icon-24,.svg-icon-24-button{
cursor:pointer;
height:24px;
width:24px;
min-width:24px
}
.touch-icon{
margin:-12px;
padding:12px
}
.touch-icon:active,.touch-icon:focus{
background-color:rgba(153,153,153,.4);
border-radius:50%
}
svg:not(:root).touch-icon{
overflow:visible
}
html[dir=rtl] .rtl-reversible-icon{
-webkit-transform:scaleX(-1);
-ms-transform:scaleX(-1);
transform:scaleX(-1)
}
.svg-icon-24-button,.touch-icon-button{
background:0 0;
border:0;
margin:0;
outline:0;
padding:0
}
.touch-icon-button .touch-icon:active,.touch-icon-button .touch-icon:focus{
background-color:transparent
}
.touch-icon-button:active .touch-icon,.touch-icon-button:focus .touch-icon{
background-color:rgba(153,153,153,.4);
border-radius:50%
}
.Profile .default-avatar-wrapper .avatar-icon{
border-radius:50%;
border:solid 1px #707070;
box-sizing:border-box;
fill:#707070;
margin:0
}
.Profile .individual .default-avatar-wrapper .avatar-icon{
padding:25px
}
.Profile .individual .avatar-icon,.Profile .individual .profile-img{
height:120px;
width:120px
}
.Profile .team .default-avatar-wrapper .avatar-icon{
padding:8px
}
.Profile .team .avatar-icon,.Profile .team .default-avatar-wrapper,.Profile .team .profile-img{
height:40px;
width:40px
}
.snippet-container{
margin:0;
position:relative;
overflow:hidden
}
.snippet-fade{
bottom:0;
box-sizing:border-box;
position:absolute;
width:96px
}
.snippet-fade{
right:0
}
.snippet-fade:after{
content:"\2026"
}
.snippet-fade:after{
float:right
}
.post-bottom{
-webkit-box-align:center;
-webkit-align-items:center;
-ms-flex-align:center;
align-items:center;
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
-webkit-flex-wrap:wrap;
-ms-flex-wrap:wrap;
flex-wrap:wrap
}
.post-footer{
-webkit-box-flex:1;
-webkit-flex:1 1 auto;
-ms-flex:1 1 auto;
flex:1 1 auto;
-webkit-flex-wrap:wrap;
-ms-flex-wrap:wrap;
flex-wrap:wrap;
-webkit-box-ordinal-group:2;
-webkit-order:1;
-ms-flex-order:1;
order:1
}
.post-footer>*{
-webkit-box-flex:0;
-webkit-flex:0 1 auto;
-ms-flex:0 1 auto;
flex:0 1 auto
}
.post-footer .byline:last-child{
margin-right:1em
}
.jump-link{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto;
-webkit-box-ordinal-group:3;
-webkit-order:2;
-ms-flex-order:2;
order:2
}
.centered-top-container.sticky{
left:0;
position:fixed;
right:0;
top:0;
width:auto;
z-index:50;
-webkit-transition-property:opacity,-webkit-transform;
transition-property:opacity,-webkit-transform;
transition-property:transform,opacity;
transition-property:transform,opacity,-webkit-transform;
-webkit-transition-duration:.2s;
transition-duration:.2s;
-webkit-transition-timing-function:cubic-bezier(.4,0,.2,1);
transition-timing-function:cubic-bezier(.4,0,.2,1)
}
.centered-top-placeholder{
display:none
}
.collapsed-header .centered-top-placeholder{
display:block
}
.centered-top-container .Header .replaced h1,.centered-top-placeholder .Header .replaced h1{
display:none
}
.centered-top-container.sticky .Header .replaced h1{
display:block
}
.centered-top-container.sticky .Header .header-widget{
background:0 0
}
.centered-top-container.sticky .Header .header-image-wrapper{
display:none
}
.centered-top-container img,.centered-top-placeholder img{
max-width:100%
}
.collapsible{
-webkit-transition:height .3s cubic-bezier(.4,0,.2,1);
transition:height .3s cubic-bezier(.4,0,.2,1)
}
.collapsible,.collapsible>summary{
display:block;
overflow:hidden
}
.collapsible>:not(summary){
display:none
}
.collapsible[open]>:not(summary){
display:block
}
.collapsible:focus,.collapsible>summary:focus{
outline:0
}
.collapsible>summary{
cursor:pointer;
display:block;
padding:0
}
.collapsible:focus>summary,.collapsible>summary:focus{
background-color:transparent
}
.collapsible>summary::-webkit-details-marker{
display:none
}
.collapsible-title{
-webkit-box-align:center;
-webkit-align-items:center;
-ms-flex-align:center;
align-items:center;
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex
}
.collapsible-title .title{
-webkit-box-flex:1;
-webkit-flex:1 1 auto;
-ms-flex:1 1 auto;
flex:1 1 auto;
-webkit-box-ordinal-group:1;
-webkit-order:0;
-ms-flex-order:0;
order:0;
overflow:hidden;
text-overflow:ellipsis;
white-space:nowrap
}
.collapsible-title .chevron-down,.collapsible[open] .collapsible-title .chevron-up{
display:block
}
.collapsible-title .chevron-up,.collapsible[open] .collapsible-title .chevron-down{
display:none
}
.flat-button{
cursor:pointer;
display:inline-block;
font-weight:700;
text-transform:uppercase;
border-radius:2px;
padding:8px;
margin:-8px
}
.flat-icon-button{
background:0 0;
border:0;
margin:0;
outline:0;
padding:0;
margin:-12px;
padding:12px;
cursor:pointer;
box-sizing:content-box;
display:inline-block;
line-height:0
}
.flat-icon-button,.flat-icon-button .splash-wrapper{
border-radius:50%
}
.flat-icon-button .splash.animate{
-webkit-animation-duration:.3s;
animation-duration:.3s
}
.overflowable-container{
max-height:46px;
overflow:hidden;
position:relative
}
.overflow-button{
cursor:pointer
}
#overflowable-dim-overlay{
background:0 0
}
.overflow-popup{
box-shadow:0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);
background-color:#ffffff;
left:0;
max-width:calc(100% - 32px);
position:absolute;
top:0;
visibility:hidden;
z-index:101
}
.overflow-popup ul{
list-style:none
}
.overflow-popup .tabs li,.overflow-popup li{
display:block;
height:auto
}
.overflow-popup .tabs li{
padding-left:0;
padding-right:0
}
.overflow-button.hidden,.overflow-popup .tabs li.hidden,.overflow-popup li.hidden{
display:none
}
.pill-button{
background:0 0;
border:1px solid;
border-radius:12px;
cursor:pointer;
display:inline-block;
padding:4px 16px;
text-transform:uppercase
}
.ripple{
position:relative
}
.ripple>*{
z-index:1
}
.splash-wrapper{
bottom:0;
left:0;
overflow:hidden;
pointer-events:none;
position:absolute;
right:0;
top:0;
z-index:0
}
.splash{
background:#ccc;
border-radius:100%;
display:block;
opacity:.6;
position:absolute;
-webkit-transform:scale(0);
-ms-transform:scale(0);
transform:scale(0)
}
.splash.animate{
-webkit-animation:ripple-effect .4s linear;
animation:ripple-effect .4s linear
}
@-webkit-keyframes ripple-effect{
100%{
opacity:0;
-webkit-transform:scale(2.5);
transform:scale(2.5)
}
}
@keyframes ripple-effect{
100%{
opacity:0;
-webkit-transform:scale(2.5);
transform:scale(2.5)
}
}
.search{
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
line-height:24px;
width:24px
}
.search.focused{
width:100%
}
.search.focused .section{
width:100%
}
.search form{
z-index:101
}
.search h3{
display:none
}
.search form{
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
-webkit-box-flex:1;
-webkit-flex:1 0 0;
-ms-flex:1 0 0px;
flex:1 0 0;
border-bottom:solid 1px transparent;
padding-bottom:8px
}
.search form>*{
display:none
}
.search.focused form>*{
display:block
}
.search .search-input label{
display:none
}
.centered-top-placeholder.cloned .search form{
z-index:30
}
.search.focused form{
border-color:#ffffff;
position:relative;
width:auto
}
.collapsed-header .centered-top-container .search.focused form{
border-bottom-color:transparent
}
.search-expand{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto
}
.search-expand-text{
display:none
}
.search-close{
display:inline;
vertical-align:middle
}
.search-input{
-webkit-box-flex:1;
-webkit-flex:1 0 1px;
-ms-flex:1 0 1px;
flex:1 0 1px
}
.search-input input{
background:0 0;
border:0;
box-sizing:border-box;
color:#ffffff;
display:inline-block;
outline:0;
width:calc(100% - 48px)
}
.search-input input.no-cursor{
color:transparent;
text-shadow:0 0 0 #ffffff
}
.collapsed-header .centered-top-container .search-action,.collapsed-header .centered-top-container .search-input input{
color:#212121
}
.collapsed-header .centered-top-container .search-input input.no-cursor{
color:transparent;
text-shadow:0 0 0 #212121
}
.collapsed-header .centered-top-container .search-input input.no-cursor:focus,.search-input input.no-cursor:focus{
outline:0
}
.search-focused>*{
visibility:hidden
}
.search-focused .search,.search-focused .search-icon{
visibility:visible
}
.search.focused .search-action{
display:block
}
.search.focused .search-action:disabled{
opacity:.3
}
.widget.Sharing .sharing-button{
display:none
}
.widget.Sharing .sharing-buttons li{
padding:0
}
.widget.Sharing .sharing-buttons li span{
display:none
}
.post-share-buttons{
position:relative
}
.centered-bottom .share-buttons .svg-icon-24,.share-buttons .svg-icon-24{
fill:#212121
}
.sharing-open.touch-icon-button:active .touch-icon,.sharing-open.touch-icon-button:focus .touch-icon{
background-color:transparent
}
.share-buttons{
background-color:#ffffff;
border-radius:2px;
box-shadow:0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);
color:#212121;
list-style:none;
margin:0;
padding:8px 0;
position:absolute;
top:-11px;
min-width:200px;
z-index:101
}
.share-buttons.hidden{
display:none
}
.sharing-button{
background:0 0;
border:0;
margin:0;
outline:0;
padding:0;
cursor:pointer
}
.share-buttons li{
margin:0;
height:48px
}
.share-buttons li:last-child{
margin-bottom:0
}
.share-buttons li .sharing-platform-button{
box-sizing:border-box;
cursor:pointer;
display:block;
height:100%;
margin-bottom:0;
padding:0 16px;
position:relative;
width:100%
}
.share-buttons li .sharing-platform-button:focus,.share-buttons li .sharing-platform-button:hover{
background-color:rgba(128,128,128,.1);
outline:0
}
.share-buttons li svg[class*=" sharing-"],.share-buttons li svg[class^=sharing-]{
position:absolute;
top:10px
}
.share-buttons li span.sharing-platform-button{
position:relative;
top:0
}
.share-buttons li .platform-sharing-text{
display:block;
font-size:16px;
line-height:48px;
white-space:nowrap
}
.share-buttons li .platform-sharing-text{
margin-left:56px
}
.sidebar-container{
background-color:#ffffff;
max-width:284px;
overflow-y:auto;
-webkit-transition-property:-webkit-transform;
transition-property:-webkit-transform;
transition-property:transform;
transition-property:transform,-webkit-transform;
-webkit-transition-duration:.3s;
transition-duration:.3s;
-webkit-transition-timing-function:cubic-bezier(0,0,.2,1);
transition-timing-function:cubic-bezier(0,0,.2,1);
width:284px;
z-index:101;
-webkit-overflow-scrolling:touch
}
.sidebar-container .navigation{
line-height:0;
padding:16px
}
.sidebar-container .sidebar-back{
cursor:pointer
}
.sidebar-container .widget{
background:0 0;
margin:0 16px;
padding:16px 0
}
.sidebar-container .widget .title{
color:#212121;
margin:0
}
.sidebar-container .widget ul{
list-style:none;
margin:0;
padding:0
}
.sidebar-container .widget ul ul{
margin-left:1em
}
.sidebar-container .widget li{
font-size:16px;
line-height:normal
}
.sidebar-container .widget+.widget{
border-top:1px dashed #cccccc
}
.BlogArchive li{
margin:16px 0
}
.BlogArchive li:last-child{
margin-bottom:0
}
.Label li a{
display:inline-block
}
.BlogArchive .post-count,.Label .label-count{
float:right;
margin-left:.25em
}
.BlogArchive .post-count::before,.Label .label-count::before{
content:"("
}
.BlogArchive .post-count::after,.Label .label-count::after{
content:")"
}
.widget.Translate .skiptranslate>div{
display:block!important
}
.widget.Profile .profile-link{
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex
}
.widget.Profile .team-member .default-avatar-wrapper,.widget.Profile .team-member .profile-img{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto;
margin-right:1em
}
.widget.Profile .individual .profile-link{
-webkit-box-orient:vertical;
-webkit-box-direction:normal;
-webkit-flex-direction:column;
-ms-flex-direction:column;
flex-direction:column
}
.widget.Profile .team .profile-link .profile-name{
-webkit-align-self:center;
-ms-flex-item-align:center;
align-self:center;
display:block;
-webkit-box-flex:1;
-webkit-flex:1 1 auto;
-ms-flex:1 1 auto;
flex:1 1 auto
}
.dim-overlay{
background-color:rgba(0,0,0,.54);
z-index:100
}
body.sidebar-visible{
overflow-y:hidden
}
@media screen and (max-width:1439px){
.sidebar-container{
bottom:0;
position:fixed;
top:0;
left:0;
right:auto
}
.sidebar-container.sidebar-invisible{
-webkit-transition-timing-function:cubic-bezier(.4,0,.6,1);
transition-timing-function:cubic-bezier(.4,0,.6,1);
-webkit-transform:translateX(-284px);
-ms-transform:translateX(-284px);
transform:translateX(-284px)
}
}
@media screen and (min-width:1440px){
.sidebar-container{
position:absolute;
top:0;
left:0;
right:auto
}
.sidebar-container .navigation{
display:none
}
}
.dialog{
box-shadow:0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);
background:#ffffff;
box-sizing:border-box;
color:#757575;
padding:30px;
position:fixed;
text-align:center;
width:calc(100% - 24px);
z-index:101
}
.dialog input[type=email],.dialog input[type=text]{
background-color:transparent;
border:0;
border-bottom:solid 1px rgba(117,117,117,.12);
color:#757575;
display:block;
font-family:Roboto, sans-serif;
font-size:16px;
line-height:24px;
margin:auto;
padding-bottom:7px;
outline:0;
text-align:center;
width:100%
}
.dialog input[type=email]::-webkit-input-placeholder,.dialog input[type=text]::-webkit-input-placeholder{
color:#757575
}
.dialog input[type=email]::-moz-placeholder,.dialog input[type=text]::-moz-placeholder{
color:#757575
}
.dialog input[type=email]:-ms-input-placeholder,.dialog input[type=text]:-ms-input-placeholder{
color:#757575
}
.dialog input[type=email]::-ms-input-placeholder,.dialog input[type=text]::-ms-input-placeholder{
color:#757575
}
.dialog input[type=email]::placeholder,.dialog input[type=text]::placeholder{
color:#757575
}
.dialog input[type=email]:focus,.dialog input[type=text]:focus{
border-bottom:solid 2px #2196f3;
padding-bottom:6px
}
.dialog input.no-cursor{
color:transparent;
text-shadow:0 0 0 #757575
}
.dialog input.no-cursor:focus{
outline:0
}
.dialog input.no-cursor:focus{
outline:0
}
.dialog input[type=submit]{
font-family:Roboto, sans-serif
}
.dialog .goog-buttonset-default{
color:#2196f3
}
.subscribe-popup{
max-width:364px
}
.subscribe-popup h3{
color:#212121;
font-size:1.8em;
margin-top:0
}
.subscribe-popup .FollowByEmail h3{
display:none
}
.subscribe-popup .FollowByEmail .follow-by-email-submit{
color:#2196f3;
display:inline-block;
margin:0 auto;
margin-top:24px;
width:auto;
white-space:normal
}
.subscribe-popup .FollowByEmail .follow-by-email-submit:disabled{
cursor:default;
opacity:.3
}
@media (max-width:800px){
.blog-name div.widget.Subscribe{
margin-bottom:16px
}
body.item-view .blog-name div.widget.Subscribe{
margin:8px auto 16px auto;
width:100%
}
}
.tabs{
list-style:none
}
.tabs li{
display:inline-block
}
.tabs li a{
cursor:pointer;
display:inline-block;
font-weight:700;
text-transform:uppercase;
padding:12px 8px
}
.tabs .selected{
border-bottom:4px solid #ffffff
}
.tabs .selected a{
color:#ffffff
}
body#layout .bg-photo,body#layout .bg-photo-overlay{
display:none
}
body#layout .page_body{
padding:0;
position:relative;
top:0
}
body#layout .page{
display:inline-block;
left:inherit;
position:relative;
vertical-align:top;
width:540px
}
body#layout .centered{
max-width:954px
}
body#layout .navigation{
display:none
}
body#layout .sidebar-container{
display:inline-block;
width:40%
}
body#layout .hamburger-menu,body#layout .search{
display:none
}
.centered-top-container .svg-icon-24,body.collapsed-header .centered-top-placeholder .svg-icon-24{
fill:#ffffff
}
.sidebar-container .svg-icon-24{
fill:#707070
}
.centered-bottom .svg-icon-24,body.collapsed-header .centered-top-container .svg-icon-24{
fill:#707070
}
.centered-bottom .share-buttons .svg-icon-24,.share-buttons .svg-icon-24{
fill:#212121
}
body{
background-color:#eeeeee;
color:#757575;
font:15px Roboto, sans-serif;
margin:0;
min-height:100vh
}
img{
max-width:100%
}
h3{
color:#757575;
font-size:16px
}
a{
text-decoration:none;
color:#2196f3
}
a:visited{
color:#2196f3
}
a:hover{
color:#2196f3
}
blockquote{
color:#444444;
font:italic 300 15px Roboto, sans-serif;
font-size:x-large;
text-align:center
}
.pill-button{
font-size:12px
}
.bg-photo-container{
height:480px;
overflow:hidden;
position:absolute;
width:100%;
z-index:1
}
.bg-photo{
background:#eeeeee url(https://blogger.googleusercontent.com/img/a/AVvXsEh-uQtxmOj2KZVjMfLGkIaQQSqxMk0K7urx3MIw5Mm33X8hD1NA3Mq523e7K4n9Ye8a_AdNElNz0NnrIAd1j9G4jgsaZQ91JipoV5tEHINGR0OI4nus7biZypt7d0jg_ZXI0jqVn10r1IVVRvvZblaeQqyFKxL7BujNBKhi2gb1dovG4QaISQbvB8nRudk=s1600) repeat scroll top left;
background-attachment:scroll;
background-size:cover;
-webkit-filter:blur(0px);
filter:blur(0px);
height:calc(100% + 2 * 0px);
left:0px;
position:absolute;
top:0px;
width:calc(100% + 2 * 0px)
}
.bg-photo-overlay{
background:rgba(0,0,0,.26);
background-size:cover;
height:480px;
position:absolute;
width:100%;
z-index:2
}
.hamburger-menu{
float:left;
margin-top:0
}
.sticky .hamburger-menu{
float:none;
position:absolute
}
.search{
border-bottom:solid 1px rgba(255, 255, 255, 0);
float:right;
position:relative;
-webkit-transition-property:width;
transition-property:width;
-webkit-transition-duration:.5s;
transition-duration:.5s;
-webkit-transition-timing-function:cubic-bezier(.4,0,.2,1);
transition-timing-function:cubic-bezier(.4,0,.2,1);
z-index:101
}
.search .dim-overlay{
background-color:transparent
}
.search form{
height:36px;
-webkit-transition-property:border-color;
transition-property:border-color;
-webkit-transition-delay:.5s;
transition-delay:.5s;
-webkit-transition-duration:.2s;
transition-duration:.2s;
-webkit-transition-timing-function:cubic-bezier(.4,0,.2,1);
transition-timing-function:cubic-bezier(.4,0,.2,1)
}
.search.focused{
width:calc(100% - 48px)
}
.search.focused form{
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
-webkit-box-flex:1;
-webkit-flex:1 0 1px;
-ms-flex:1 0 1px;
flex:1 0 1px;
border-color:#ffffff;
margin-left:-24px;
padding-left:36px;
position:relative;
width:auto
}
.item-view .search,.sticky .search{
right:0;
float:none;
margin-left:0;
position:absolute
}
.item-view .search.focused,.sticky .search.focused{
width:calc(100% - 50px)
}
.item-view .search.focused form,.sticky .search.focused form{
border-bottom-color:#757575
}
.centered-top-placeholder.cloned .search form{
z-index:30
}
.search_button{
-webkit-box-flex:0;
-webkit-flex:0 0 24px;
-ms-flex:0 0 24px;
flex:0 0 24px;
-webkit-box-orient:vertical;
-webkit-box-direction:normal;
-webkit-flex-direction:column;
-ms-flex-direction:column;
flex-direction:column
}
.search_button svg{
margin-top:0
}
.search-input{
height:48px
}
.search-input input{
display:block;
color:#ffffff;
font:16px Roboto, sans-serif;
height:48px;
line-height:48px;
padding:0;
width:100%
}
.search-input input::-webkit-input-placeholder{
color:#ffffff;
opacity:.3
}
.search-input input::-moz-placeholder{
color:#ffffff;
opacity:.3
}
.search-input input:-ms-input-placeholder{
color:#ffffff;
opacity:.3
}
.search-input input::-ms-input-placeholder{
color:#ffffff;
opacity:.3
}
.search-input input::placeholder{
color:#ffffff;
opacity:.3
}
.search-action{
background:0 0;
border:0;
color:#ffffff;
cursor:pointer;
display:none;
height:48px;
margin-top:0
}
.sticky .search-action{
color:#757575
}
.search.focused .search-action{
display:block
}
.search.focused .search-action:disabled{
opacity:.3
}
.page_body{
position:relative;
z-index:20
}
.page_body .widget{
margin-bottom:16px
}
.page_body .centered{
box-sizing:border-box;
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
-webkit-box-orient:vertical;
-webkit-box-direction:normal;
-webkit-flex-direction:column;
-ms-flex-direction:column;
flex-direction:column;
margin:0 auto;
max-width:922px;
min-height:100vh;
padding:24px 0
}
.page_body .centered>*{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto
}
.page_body .centered>#footer{
margin-top:auto
}
.blog-name{
margin:24px 0 16px 0
}
.item-view .blog-name,.sticky .blog-name{
box-sizing:border-box;
margin-left:36px;
min-height:48px;
opacity:1;
padding-top:12px
}
.blog-name .subscribe-section-container{
margin-bottom:32px;
text-align:center;
-webkit-transition-property:opacity;
transition-property:opacity;
-webkit-transition-duration:.5s;
transition-duration:.5s
}
.item-view .blog-name .subscribe-section-container,.sticky .blog-name .subscribe-section-container{
margin:0 0 8px 0
}
.blog-name .PageList{
margin-top:16px;
padding-top:8px;
text-align:center
}
.blog-name .PageList .overflowable-contents{
width:100%
}
.blog-name .PageList h3.title{
color:#ffffff;
margin:8px auto;
text-align:center;
width:100%
}
.centered-top-container .blog-name{
-webkit-transition-property:opacity;
transition-property:opacity;
-webkit-transition-duration:.5s;
transition-duration:.5s
}
.item-view .return_link{
margin-bottom:12px;
margin-top:12px;
position:absolute
}
.item-view .blog-name{
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
-webkit-flex-wrap:wrap;
-ms-flex-wrap:wrap;
flex-wrap:wrap;
margin:0 48px 27px 48px
}
.item-view .subscribe-section-container{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto
}
.item-view #header,.item-view .Header{
margin-bottom:5px;
margin-right:15px
}
.item-view .sticky .Header{
margin-bottom:0
}
.item-view .Header p{
margin:10px 0 0 0;
text-align:left
}
.item-view .post-share-buttons-bottom{
margin-right:16px
}
.sticky{
background:#ffffff;
box-shadow:0 0 20px 0 rgba(0,0,0,.7);
box-sizing:border-box;
margin-left:0
}
.sticky #header{
margin-bottom:8px;
margin-right:8px
}
.sticky .centered-top{
margin:4px auto;
max-width:890px;
min-height:48px
}
.sticky .blog-name{
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
margin:0 48px
}
.sticky .blog-name #header{
-webkit-box-flex:0;
-webkit-flex:0 1 auto;
-ms-flex:0 1 auto;
flex:0 1 auto;
-webkit-box-ordinal-group:2;
-webkit-order:1;
-ms-flex-order:1;
order:1;
overflow:hidden
}
.sticky .blog-name .subscribe-section-container{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto;
-webkit-box-ordinal-group:3;
-webkit-order:2;
-ms-flex-order:2;
order:2
}
.sticky .Header h1{
overflow:hidden;
text-overflow:ellipsis;
white-space:nowrap;
margin-right:-10px;
margin-bottom:-10px;
padding-right:10px;
padding-bottom:10px
}
.sticky .Header p{
display:none
}
.sticky .PageList{
display:none
}
.search-focused>*{
visibility:visible
}
.search-focused .hamburger-menu{
visibility:visible
}
.item-view .search-focused .blog-name,.sticky .search-focused .blog-name{
opacity:0
}
.centered-bottom,.centered-top-container,.centered-top-placeholder{
padding:0 16px
}
.centered-top{
position:relative
}
.item-view .centered-top.search-focused .subscribe-section-container,.sticky .centered-top.search-focused .subscribe-section-container{
opacity:0
}
.page_body.has-vertical-ads .centered .centered-bottom{
display:inline-block;
width:calc(100% - 176px)
}
.Header h1{
color:#ffffff;
font:bold 45px Roboto, sans-serif;
line-height:normal;
margin:0 0 13px 0;
text-align:center;
width:100%
}
.Header h1 a,.Header h1 a:hover,.Header h1 a:visited{
color:#ffffff
}
.item-view .Header h1,.sticky .Header h1{
font-size:24px;
line-height:24px;
margin:0;
text-align:left
}
.sticky .Header h1{
color:#757575
}
.sticky .Header h1 a,.sticky .Header h1 a:hover,.sticky .Header h1 a:visited{
color:#757575
}
.Header p{
color:#ffffff;
margin:0 0 13px 0;
opacity:.8;
text-align:center
}
.widget .title{
line-height:28px
}
.BlogArchive li{
font-size:16px
}
.BlogArchive .post-count{
color:#757575
}
#page_body .FeaturedPost,.Blog .blog-posts .post-outer-container{
background:#ffffff;
min-height:40px;
padding:30px 40px;
width:auto
}
.Blog .blog-posts .post-outer-container:last-child{
margin-bottom:0
}
.Blog .blog-posts .post-outer-container .post-outer{
border:0;
position:relative;
padding-bottom:.25em
}
.post-outer-container{
margin-bottom:16px
}
.post:first-child{
margin-top:0
}
.post .thumb{
float:left;
height:20%;
width:20%
}
.post-share-buttons-bottom,.post-share-buttons-top{
float:right
}
.post-share-buttons-bottom{
margin-right:24px
}
.post-footer,.post-header{
clear:left;
color:#000000;
margin:0;
width:inherit
}
.blog-pager{
text-align:center
}
.blog-pager a{
color:#2196f3
}
.blog-pager a:visited{
color:#2196f3
}
.blog-pager a:hover{
color:#2196f3
}
.post-title{
font:bold 22px Roboto, sans-serif;
float:left;
margin:0 0 8px 0;
max-width:calc(100% - 48px)
}
.post-title a{
font:bold 30px Roboto, sans-serif
}
.post-title,.post-title a,.post-title a:hover,.post-title a:visited{
color:#212121
}
.post-body{
color:#757575;
font:15px Roboto, sans-serif;
line-height:1.6em;
margin:1.5em 0 2em 0;
display:block
}
.post-body img{
height:inherit
}
.post-body .snippet-thumbnail{
float:left;
margin:0;
margin-right:2em;
max-height:128px;
max-width:128px
}
.post-body .snippet-thumbnail img{
max-width:100%
}
.main .FeaturedPost .widget-content{
border:0;
position:relative;
padding-bottom:.25em
}
.FeaturedPost img{
margin-top:2em
}
.FeaturedPost .snippet-container{
margin:2em 0
}
.FeaturedPost .snippet-container p{
margin:0
}
.FeaturedPost .snippet-thumbnail{
float:none;
height:auto;
margin-bottom:2em;
margin-right:0;
overflow:hidden;
max-height:calc(600px + 2em);
max-width:100%;
text-align:center;
width:100%
}
.FeaturedPost .snippet-thumbnail img{
max-width:100%;
width:100%
}
.byline{
color:#000000;
display:inline-block;
line-height:24px;
margin-top:8px;
vertical-align:top
}
.byline.post-author:first-child{
margin-right:0
}
.byline.reactions .reactions-label{
line-height:22px;
vertical-align:top
}
.byline.post-share-buttons{
position:relative;
display:inline-block;
margin-top:0;
width:100%
}
.byline.post-share-buttons .sharing{
float:right
}
.flat-button.ripple:hover{
background-color:rgba(33,150,243,.12)
}
.flat-button.ripple .splash{
background-color:rgba(33,150,243,.4)
}
a.timestamp-link,a:active.timestamp-link,a:visited.timestamp-link{
color:inherit;
font:inherit;
text-decoration:inherit
}
.post-share-buttons{
margin-left:0
}
.clear-sharing{
min-height:24px
}
.comment-link{
color:#2196f3;
position:relative
}
.comment-link .num_comments{
margin-left:8px;
vertical-align:top
}
#comment-holder .continue{
display:none
}
#comment-editor{
margin-bottom:20px;
margin-top:20px
}
#comments .comment-form h4,#comments h3.title{
position:absolute;
clip:rect(1px,1px,1px,1px);
padding:0;
border:0;
height:1px;
width:1px;
overflow:hidden
}
.post-filter-message{
background-color:rgba(0,0,0,.7);
color:#fff;
display:table;
margin-bottom:16px;
width:100%
}
.post-filter-message div{
display:table-cell;
padding:15px 28px
}
.post-filter-message div:last-child{
padding-left:0;
text-align:right
}
.post-filter-message a{
white-space:nowrap
}
.post-filter-message .search-label,.post-filter-message .search-query{
font-weight:700;
color:#2196f3
}
#blog-pager{
margin:2em 0
}
#blog-pager a{
color:#2196f3;
font-size:14px
}
.subscribe-button{
border-color:#ffffff;
color:#ffffff
}
.sticky .subscribe-button{
border-color:#757575;
color:#757575
}
.tabs{
margin:0 auto;
padding:0
}
.tabs li{
margin:0 8px;
vertical-align:top
}
.tabs .overflow-button a,.tabs li a{
color:#cccccc;
font:700 normal 15px Roboto, sans-serif;
line-height:18px
}
.tabs .overflow-button a{
padding:12px 8px
}
.overflow-popup .tabs li{
text-align:left
}
.overflow-popup li a{
color:#757575;
display:block;
padding:8px 20px
}
.overflow-popup li.selected a{
color:#212121
}
a.report_abuse{
font-weight:400
}
.Label li,.Label span.label-size,.byline.post-labels a{
background-color:#f7f7f7;
border:1px solid #f7f7f7;
border-radius:15px;
display:inline-block;
margin:4px 4px 4px 0;
padding:3px 8px
}
.Label a,.byline.post-labels a{
color:#000000
}
.Label ul{
list-style:none;
padding:0
}
.PopularPosts{
background-color:#eeeeee;
padding:30px 40px
}
.PopularPosts .item-content{
color:#757575;
margin-top:24px
}
.PopularPosts a,.PopularPosts a:hover,.PopularPosts a:visited{
color:#2196f3
}
.PopularPosts .post-title,.PopularPosts .post-title a,.PopularPosts .post-title a:hover,.PopularPosts .post-title a:visited{
color:#212121;
font-size:18px;
font-weight:700;
line-height:24px
}
.PopularPosts,.PopularPosts h3.title a{
color:#757575;
font:15px Roboto, sans-serif
}
.main .PopularPosts{
padding:16px 40px
}
.PopularPosts h3.title{
font-size:14px;
margin:0
}
.PopularPosts h3.post-title{
margin-bottom:0
}
.PopularPosts .byline{
color:#000000
}
.PopularPosts .jump-link{
float:right;
margin-top:16px
}
.PopularPosts .post-header .byline{
font-size:.9em;
font-style:italic;
margin-top:6px
}
.PopularPosts ul{
list-style:none;
padding:0;
margin:0
}
.PopularPosts .post{
padding:20px 0
}
.PopularPosts .post+.post{
border-top:1px dashed #cccccc
}
.PopularPosts .item-thumbnail{
float:left;
margin-right:32px
}
.PopularPosts .item-thumbnail img{
height:88px;
padding:0;
width:88px
}
.inline-ad{
margin-bottom:16px
}
.desktop-ad .inline-ad{
display:block
}
.adsbygoogle{
overflow:hidden
}
.vertical-ad-container{
float:right;
margin-right:16px;
width:128px
}
.vertical-ad-container .AdSense+.AdSense{
margin-top:16px
}
.inline-ad-placeholder,.vertical-ad-placeholder{
background:#ffffff;
border:1px solid #000;
opacity:.9;
vertical-align:middle;
text-align:center
}
.inline-ad-placeholder span,.vertical-ad-placeholder span{
margin-top:290px;
display:block;
text-transform:uppercase;
font-weight:700;
color:#212121
}
.vertical-ad-placeholder{
height:600px
}
.vertical-ad-placeholder span{
margin-top:290px;
padding:0 40px
}
.inline-ad-placeholder{
height:90px
}
.inline-ad-placeholder span{
margin-top:36px
}
.Attribution{
color:#757575
}
.Attribution a,.Attribution a:hover,.Attribution a:visited{
color:#2196f3
}
.Attribution svg{
fill:#707070
}
.sidebar-container{
box-shadow:1px 1px 3px rgba(0,0,0,.1)
}
.sidebar-container,.sidebar-container .sidebar_bottom{
background-color:#ffffff
}
.sidebar-container .navigation,.sidebar-container .sidebar_top_wrapper{
background-color:#ffffff
}
.sidebar-container .sidebar_top{
overflow:auto
}
.sidebar-container .sidebar_bottom{
width:100%;
padding-top:16px
}
.sidebar-container .widget:first-child{
padding-top:0
}
.sidebar_top .widget.Profile{
padding-bottom:16px
}
.widget.Profile{
margin:0;
width:100%
}
.widget.Profile h2{
display:none
}
.widget.Profile h3.title{
color:#000000;
margin:16px 32px
}
.widget.Profile .individual{
text-align:center
}
.widget.Profile .individual .profile-link{
padding:1em
}
.widget.Profile .individual .default-avatar-wrapper .avatar-icon{
margin:auto
}
.widget.Profile .team{
margin-bottom:32px;
margin-left:32px;
margin-right:32px
}
.widget.Profile ul{
list-style:none;
padding:0
}
.widget.Profile li{
margin:10px 0
}
.widget.Profile .profile-img{
border-radius:50%;
float:none
}
.widget.Profile .profile-link{
color:#212121;
font-size:.9em;
margin-bottom:1em;
opacity:.87;
overflow:hidden
}
.widget.Profile .profile-link.visit-profile{
border-style:solid;
border-width:1px;
border-radius:12px;
cursor:pointer;
font-size:12px;
font-weight:400;
padding:5px 20px;
display:inline-block;
line-height:normal
}
.widget.Profile dd{
color:#000000;
margin:0 16px
}
.widget.Profile location{
margin-bottom:1em
}
.widget.Profile .profile-textblock{
font-size:14px;
line-height:24px;
position:relative
}
body.sidebar-visible .page_body{
overflow-y:scroll
}
body.sidebar-visible .bg-photo-container{
overflow-y:scroll
}
@media screen and (min-width:1440px){
.sidebar-container{
margin-top:480px;
min-height:calc(100% - 480px);
overflow:visible;
z-index:32
}
.sidebar-container .sidebar_top_wrapper{
background-color:#f7f7f7;
height:480px;
margin-top:-480px
}
.sidebar-container .sidebar_top{
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
height:480px;
-webkit-box-orient:horizontal;
-webkit-box-direction:normal;
-webkit-flex-direction:row;
-ms-flex-direction:row;
flex-direction:row;
max-height:480px
}
.sidebar-container .sidebar_bottom{
max-width:284px;
width:284px
}
body.collapsed-header .sidebar-container{
z-index:15
}
.sidebar-container .sidebar_top:empty{
display:none
}
.sidebar-container .sidebar_top>:only-child{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto;
-webkit-align-self:center;
-ms-flex-item-align:center;
align-self:center;
width:100%
}
.sidebar_top_wrapper.no-items{
display:none
}
}
.post-snippet.snippet-container{
max-height:120px
}
.post-snippet .snippet-item{
line-height:24px
}
.post-snippet .snippet-fade{
background:-webkit-linear-gradient(left,#ffffff 0,#ffffff 20%,rgba(255, 255, 255, 0) 100%);
background:linear-gradient(to left,#ffffff 0,#ffffff 20%,rgba(255, 255, 255, 0) 100%);
color:#757575;
height:24px
}
.popular-posts-snippet.snippet-container{
max-height:72px
}
.popular-posts-snippet .snippet-item{
line-height:24px
}
.PopularPosts .popular-posts-snippet .snippet-fade{
color:#757575;
height:24px
}
.main .popular-posts-snippet .snippet-fade{
background:-webkit-linear-gradient(left,#eeeeee 0,#eeeeee 20%,rgba(238, 238, 238, 0) 100%);
background:linear-gradient(to left,#eeeeee 0,#eeeeee 20%,rgba(238, 238, 238, 0) 100%)
}
.sidebar_bottom .popular-posts-snippet .snippet-fade{
background:-webkit-linear-gradient(left,#ffffff 0,#ffffff 20%,rgba(255, 255, 255, 0) 100%);
background:linear-gradient(to left,#ffffff 0,#ffffff 20%,rgba(255, 255, 255, 0) 100%)
}
.profile-snippet.snippet-container{
max-height:192px
}
.has-location .profile-snippet.snippet-container{
max-height:144px
}
.profile-snippet .snippet-item{
line-height:24px
}
.profile-snippet .snippet-fade{
background:-webkit-linear-gradient(left,#ffffff 0,#ffffff 20%,rgba(255, 255, 255, 0) 100%);
background:linear-gradient(to left,#ffffff 0,#ffffff 20%,rgba(255, 255, 255, 0) 100%);
color:#000000;
height:24px
}
@media screen and (min-width:1440px){
.profile-snippet .snippet-fade{
background:-webkit-linear-gradient(left,#f7f7f7 0,#f7f7f7 20%,rgba(247, 247, 247, 0) 100%);
background:linear-gradient(to left,#f7f7f7 0,#f7f7f7 20%,rgba(247, 247, 247, 0) 100%)
}
}
@media screen and (max-width:800px){
.blog-name{
margin-top:0
}
body.item-view .blog-name{
margin:0 48px
}
.centered-bottom{
padding:8px
}
body.item-view .centered-bottom{
padding:0
}
.page_body .centered{
padding:10px 0
}
body.item-view #header,body.item-view .widget.Header{
margin-right:0
}
body.collapsed-header .centered-top-container .blog-name{
display:block
}
body.collapsed-header .centered-top-container .widget.Header h1{
text-align:center
}
.widget.Header header{
padding:0
}
.widget.Header h1{
font-size:24px;
line-height:24px;
margin-bottom:13px
}
body.item-view .widget.Header h1{
text-align:center
}
body.item-view .widget.Header p{
text-align:center
}
.blog-name .widget.PageList{
padding:0
}
body.item-view .centered-top{
margin-bottom:5px
}
.search-action,.search-input{
margin-bottom:-8px
}
.search form{
margin-bottom:8px
}
body.item-view .subscribe-section-container{
margin:5px 0 0 0;
width:100%
}
#page_body.section div.widget.FeaturedPost,div.widget.PopularPosts{
padding:16px
}
div.widget.Blog .blog-posts .post-outer-container{
padding:16px
}
div.widget.Blog .blog-posts .post-outer-container .post-outer{
padding:0
}
.post:first-child{
margin:0
}
.post-body .snippet-thumbnail{
margin:0 3vw 3vw 0
}
.post-body .snippet-thumbnail img{
height:20vw;
width:20vw;
max-height:128px;
max-width:128px
}
div.widget.PopularPosts div.item-thumbnail{
margin:0 3vw 3vw 0
}
div.widget.PopularPosts div.item-thumbnail img{
height:20vw;
width:20vw;
max-height:88px;
max-width:88px
}
.post-title{
line-height:1
}
.post-title,.post-title a{
font-size:20px
}
#page_body.section div.widget.FeaturedPost h3 a{
font-size:22px
}
.mobile-ad .inline-ad{
display:block
}
.page_body.has-vertical-ads .vertical-ad-container,.page_body.has-vertical-ads .vertical-ad-container ins{
display:none
}
.page_body.has-vertical-ads .centered .centered-bottom,.page_body.has-vertical-ads .centered .centered-top{
display:block;
width:auto
}
div.post-filter-message div{
padding:8px 16px
}
}
@media screen and (min-width:1440px){
body{
position:relative
}
body.item-view .blog-name{
margin-left:48px
}
.page_body{
margin-left:284px
}
.search{
margin-left:0
}
.search.focused{
width:100%
}
.sticky{
padding-left:284px
}
.hamburger-menu{
display:none
}
body.collapsed-header .page_body .centered-top-container{
padding-left:284px;
padding-right:0;
width:100%
}
body.collapsed-header .centered-top-container .search.focused{
width:100%
}
body.collapsed-header .centered-top-container .blog-name{
margin-left:0
}
body.collapsed-header.item-view .centered-top-container .search.focused{
width:calc(100% - 50px)
}
body.collapsed-header.item-view .centered-top-container .blog-name{
margin-left:40px
}
}
-->
<!--
body#layout .hidden,
body#layout .invisible {
display: inherit;
}
body#layout .navigation {
display: none;
}
body#layout .page,
body#layout .sidebar_top,
body#layout .sidebar_bottom {
display: inline-block;
left: inherit;
position: relative;
vertical-align: top;
}
body#layout .page {
float: right;
margin-left: 20px;
width: 55%;
}
body#layout .sidebar-container {
float: right;
width: 40%;
}
body#layout .hamburger-menu {
display: none;
}
-->
    .bg-photo {background-image:url(https\:\/\/blogger.googleusercontent.com\/img\/a\/AVvXsEh-uQtxmOj2KZVjMfLGkIaQQSqxMk0K7urx3MIw5Mm33X8hD1NA3Mq523e7K4n9Ye8a_AdNElNz0NnrIAd1j9G4jgsaZQ91JipoV5tEHINGR0OI4nus7biZypt7d0jg_ZXI0jqVn10r1IVVRvvZblaeQqyFKxL7BujNBKhi2gb1dovG4QaISQbvB8nRudk=s1600);}
@media (max-width: 480px) { .bg-photo {background-image:url(https\:\/\/blogger.googleusercontent.com\/img\/a\/AVvXsEh-uQtxmOj2KZVjMfLGkIaQQSqxMk0K7urx3MIw5Mm33X8hD1NA3Mq523e7K4n9Ye8a_AdNElNz0NnrIAd1j9G4jgsaZQ91JipoV5tEHINGR0OI4nus7biZypt7d0jg_ZXI0jqVn10r1IVVRvvZblaeQqyFKxL7BujNBKhi2gb1dovG4QaISQbvB8nRudk=w480);}}
@media (max-width: 640px) and (min-width: 481px) { .bg-photo {background-image:url(https\:\/\/blogger.googleusercontent.com\/img\/a\/AVvXsEh-uQtxmOj2KZVjMfLGkIaQQSqxMk0K7urx3MIw5Mm33X8hD1NA3Mq523e7K4n9Ye8a_AdNElNz0NnrIAd1j9G4jgsaZQ91JipoV5tEHINGR0OI4nus7biZypt7d0jg_ZXI0jqVn10r1IVVRvvZblaeQqyFKxL7BujNBKhi2gb1dovG4QaISQbvB8nRudk=w640);}}
@media (max-width: 800px) and (min-width: 641px) { .bg-photo {background-image:url(https\:\/\/blogger.googleusercontent.com\/img\/a\/AVvXsEh-uQtxmOj2KZVjMfLGkIaQQSqxMk0K7urx3MIw5Mm33X8hD1NA3Mq523e7K4n9Ye8a_AdNElNz0NnrIAd1j9G4jgsaZQ91JipoV5tEHINGR0OI4nus7biZypt7d0jg_ZXI0jqVn10r1IVVRvvZblaeQqyFKxL7BujNBKhi2gb1dovG4QaISQbvB8nRudk=w800);}}
@media (max-width: 1200px) and (min-width: 801px) { .bg-photo {background-image:url(https\:\/\/blogger.googleusercontent.com\/img\/a\/AVvXsEh-uQtxmOj2KZVjMfLGkIaQQSqxMk0K7urx3MIw5Mm33X8hD1NA3Mq523e7K4n9Ye8a_AdNElNz0NnrIAd1j9G4jgsaZQ91JipoV5tEHINGR0OI4nus7biZypt7d0jg_ZXI0jqVn10r1IVVRvvZblaeQqyFKxL7BujNBKhi2gb1dovG4QaISQbvB8nRudk=w1200);}}
/* Last tag covers anything over one higher than the previous max-size cap. */
@media (min-width: 1201px) { .bg-photo {background-image:url(https\:\/\/blogger.googleusercontent.com\/img\/a\/AVvXsEh-uQtxmOj2KZVjMfLGkIaQQSqxMk0K7urx3MIw5Mm33X8hD1NA3Mq523e7K4n9Ye8a_AdNElNz0NnrIAd1j9G4jgsaZQ91JipoV5tEHINGR0OI4nus7biZypt7d0jg_ZXI0jqVn10r1IVVRvvZblaeQqyFKxL7BujNBKhi2gb1dovG4QaISQbvB8nRudk=w1600);}}
  // Supply ads personalization default for EEA readers
  // See https://www.blogger.com/go/adspersonalization
  adsbygoogle = window.adsbygoogle || [];
  if (typeof adsbygoogle.requestNonPersonalizedAds === 'undefined') {
    adsbygoogle.requestNonPersonalizedAds = 1;
  }
Ir al contenido principal
Buscar este blog
Genbyte
Inicio
Mi canal Youtube
Newsletter
Más…
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-5584594928588539"
     data-ad-host="ca-host-pub-1556223355139109"
     data-ad-slot="9197290200"
     data-ad-format="auto"
     data-full-width-responsive="true">
(adsbygoogle = window.adsbygoogle || []).push({});
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-5584594928588539"
     data-ad-host="ca-host-pub-1556223355139109"
     data-ad-slot="3281162276"
     data-ad-format="auto"
     data-full-width-responsive="true">
(adsbygoogle = window.adsbygoogle || []).push({});
{
  "@context": "http://schema.org",
  "@type": "BlogPosting",
  "mainEntityOfPage": {
    "@type": "WebPage",
    "@id": "https://genbyte.blogspot.com/2026/07/como-instalar-notediscovery-en-docker.html"
  },
  "headline": "Cómo instalar NoteDiscovery en Docker - Base de conocimiento autohospedada en Docker","description": "NoteDiscovery | Knowledge Base | Docker      NoteDiscovery: Base de conocimiento autohospedada en Docker (alternativa Obsidian...","datePublished": "2026-07-08T14:05:00+02:00",
  "dateModified": "2026-07-08T14:05:00+02:00","image": {
    "@type": "ImageObject","url": "https://blogger.googleusercontent.com/img/a/AVvXsEhbPGv8wgBFqzoNHIseXbVQ4I-2eHUlCCRYJcGhhEHNC-b3O51a-fKenAjngZ1LV1YbAbw0aJyTLIKZhmX8AJQCqvV6a_Qzi-l0OrTZr2Pr8SkOD6O034-WJCbotpAJPaVT0h2f1kSu6julIJHqR5eZqUiLPM0rO0SSZnCosqL-O0oWy4zGZHOTyFNOjjU=w1200-h630-p-k-no-nu",
    "height": 630,
    "width": 1200},"publisher": {
    "@type": "Organization",
    "name": "Blogger",
    "logo": {
      "@type": "ImageObject",
      "url": "https://blogger.googleusercontent.com/img/b/U2hvZWJveA/AVvXsEgfMvYAhAbdHksiBA24JKmb2Tav6K0GviwztID3Cq4VpV96HaJfy0viIu8z1SSw_G9n5FQHZWSRao61M3e58ImahqBtr7LiOUS6m_w59IvDYwjmMcbq3fKW4JSbacqkbxTo8B90dWp0Cese92xfLMPe_tg11g/h60/",
      "width": 206,
      "height": 60
    }
  },"author": {
    "@type": "Person",
    "name": "Genbyte"
  }
}
Cómo instalar NoteDiscovery en Docker - Base de conocimiento autohospedada en Docker
Obtener enlace
Facebook
X
Pinterest
Correo electrónico
Otras aplicaciones
  .nd-post { font-family: 'Google Sans', Arial, sans-serif; max-width: 820px; margin: 0 auto; color: #2c2c2a; line-height: 1.75; }
  .nd-hero { background: linear-gradient(135deg, #2563eb 0%, #1d4ed8 100%); border-radius: 12px; padding: 2.5rem 2rem; margin-bottom: 2rem; color: #fff; }
  .nd-hero h1 { font-size: 1.8rem; font-weight: 700; margin: 0 0 0.5rem; color: #fff; line-height: 1.2; }
  .nd-hero p { margin: 0; font-size: 1rem; opacity: 0.88; }
  .nd-badge { display: inline-block; background: rgba(255,255,255,0.18); border: 1px solid rgba(255,255,255,0.35); border-radius: 20px; padding: 3px 14px; font-size: 0.78rem; margin-bottom: 1rem; letter-spacing: 0.04em; }
  .nd-section { margin-bottom: 2rem; }
  .nd-section h2 { font-size: 1.2rem; font-weight: 700; color: #1d4ed8; border-left: 4px solid #2563eb; padding-left: 0.75rem; margin-bottom: 1rem; }
  .nd-section h3 { font-size: 1.05rem; font-weight: 700; color: #1e40af; margin: 1.5rem 0 0.75rem; }
  .nd-section p { font-size: 0.97rem; color: #444441; }
  .nd-section ul { color: #444441; font-size: 0.95rem; padding-left: 1.4rem; line-height: 1.9; }
  .nd-section ol { color: #444441; font-size: 0.95rem; padding-left: 1.4rem; line-height: 1.9; }
  .nd-code { background: #1a1f2e; border-radius: 8px; padding: 0.75rem 1rem; font-family: 'Courier New', monospace; font-size: 0.87rem; color: #60a5fa; margin: 0.75rem 0; overflow-x: auto; line-height: 1.6; white-space: pre; }
  .nd-code .comment { color: #888780; }
  .nd-code .key { color: #93c5fd; }
  .nd-code .value { color: #dbeafe; }
  .nd-features-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 1rem; margin: 1.5rem 0; }
  .nd-feature-card { background: #dbeafe; border: 1px solid #93c5fd; border-radius: 10px; padding: 1rem 1.25rem; }
  .nd-feature-card h4 { font-size: 0.95rem; font-weight: 700; color: #1d4ed8; margin: 0 0 0.5rem; }
  .nd-feature-card p { font-size: 0.85rem; color: #1e40af; margin: 0; line-height: 1.6; }
  .nd-highlight { background: #dbeafe; border-left: 4px solid #2563eb; border-radius: 0 8px 8px 0; padding: 0.9rem 1.1rem; margin: 1.5rem 0; font-size: 0.93rem; color: #1d4ed8; }
  .nd-warn { background: #faeeda; border-left: 4px solid #ef9f27; border-radius: 0 8px 8px 0; padding: 0.9rem 1.1rem; margin: 1.5rem 0; font-size: 0.88rem; color: #633806; }
  .nd-tip { background: #e6f1fb; border-left: 4px solid #378add; border-radius: 0 8px 8px 0; padding: 0.9rem 1.1rem; margin: 1.5rem 0; font-size: 0.88rem; color: #0c447c; }
  .nd-divider { border: none; border-top: 1px solid #93c5fd; margin: 2rem 0; }
  .nd-refs { background: #f1efe8; border-radius: 10px; padding: 1.1rem 1.3rem; margin-bottom: 1.5rem; }
  .nd-refs h3 { font-size: 1rem; font-weight: 700; color: #3c3489; margin: 0 0 0.6rem; }
  .nd-refs ul { margin: 0; padding-left: 1.2rem; }
  .nd-refs li { font-size: 0.88rem; color: #444441; margin-bottom: 0.3rem; }
  .nd-refs a { color: #1d4ed8; text-decoration: none; }
  .nd-refs a:hover { text-decoration: underline; }
  .nd-links-box { border: 1px solid #93c5fd; border-radius: 10px; padding: 1.1rem 1.3rem; margin-bottom: 1.25rem; }
  .nd-links-box h3 { font-size: 1rem; font-weight: 700; color: #1d4ed8; margin: 0 0 0.75rem; }
  .nd-links-box a { display: block; font-size: 0.88rem; color: #1d4ed8; text-decoration: none; margin-bottom: 0.4rem; }
  .nd-links-box a:hover { text-decoration: underline; }
  .nd-social-grid { display: flex; flex-wrap: wrap; gap: 0.6rem; margin-top: 0.5rem; }
  .nd-social-pill { display: inline-flex; align-items: center; gap: 6px; background: #dbeafe; border-radius: 20px; padding: 5px 14px; font-size: 0.83rem; color: #1d4ed8; text-decoration: none; border: 1px solid #93c5fd; }
  .nd-social-pill:hover { background: #93c5fd; }
    NoteDiscovery | Knowledge Base | Docker
    NoteDiscovery: Base de conocimiento autohospedada en Docker (alternativa Obsidian Sync, Notion, Apple Notes)
    Gestor de notas Markdown con grafo de conocimiento, búsqueda full-text, backlinks bidireccionales. MCP para IA. Temas customizables. Dark mode. Offline-capable. FastAPI + Alpine.js. MIT open source.
    ¿Qué es NoteDiscovery?
      NoteDiscovery es una herramienta moderna de toma de notas self-hosted que permite construir tu propia base de conocimiento con Markdown puro, sin dependencia de servicios cloud ni vendor lock-in. Es la alternativa open source a Obsidian Sync, Notion, Roam Research, diseñada para máxima privacidad y propiedad de datos.
      Propuesta clave: Tus notas viven como archivos .md plain text en una carpeta que controlas. Puedes usar git, grep, cualquier tool sobre ellas. Editor split-pane (Markdown + preview en vivo). Grafo de conocimiento dinámico (visualiza conexiones entre notas). Búsqueda instant full-text. Backlinks bidireccionales (wikilinks). Dark mode. MCP integration para IA (Claude, Cursor). Zero database, cero complejidad. Corre en 50MB RAM. Docker one-liner setup.
      Características principales: Editor Markdown split-pane (izquierda: source, derecha: live preview sin lag). Grafo de conocimiento dinámico con visualización. Búsqueda full-text instant. Backlinks bidireccionales (wikilinks [[nota]]). Outline panel (tabla de contenidos, click-to-jump). Favoritos (star notes). Temas customizables. Dark mode + light mode. Dibujo en-app (sketches PNG). Soporte LaTeX (MathJax) para ecuaciones. Syntax highlighting (100+ lenguajes). Mermaid diagrams. Archivos adjuntos (images, PDFs, etc). Table of contents automático. URI protocols (mailto, ssh, ftp, slack, discord, etc). Plantillas custom. Sistema plugin (extensible). Multi-idioma (15+, incluyendo español). MCP server integrado (interacción IA). Almacenamiento YAML config. FastAPI backend. Alpine.js frontend (sin heavy frameworks). Healthcheck Docker. MIT open source. Compatible Obsidian (importa bóvedas). Git-friendly (version control notas).
      Para knowledge workers: Segunda cerebro privada. Base de conocimiento sin suscripción. Datos tuyos. Forever.
    Características principales
        Editor Markdown split-pane
        Source + live preview sin lag. Sintaxis highlighting.
        Grafo de conocimiento dinámico
        Visualiza conexiones entre notas. Graph view 3D.
        Búsqueda full-text instant
        Encuentra notas rápidamente. Cached search.
        Backlinks bidireccionales
        Wikilinks [[nota]]. Descubre relaciones automáticamente.
        Outline panel (TOC)
        Tabla de contenidos. Click-to-jump headings.
        Temas customizables
        Dark mode, light mode, custom themes. YAML config.
        Dibujo integrado
        In-app sketches. PNG files next to markdown.
        LaTeX + MathJax
        Ecuaciones matemáticas. Mermaid diagrams.
        MCP para IA
        Claude, Cursor, Anthropic tools. IA lee tus notas.
        Multi-idioma
        15+ idiomas. Español incluido. Locales customizables.
        Almacenamiento plain text
        Markdown files. Sin BD. Git-friendly. Portabilidad.
        Ultra-ligero
        50MB RAM. FastAPI + Alpine.js. Sin heavy frameworks.
    Requisitos del sistema
      Docker & Docker Compose
      50-100 MB RAM mínimo (ultra-ligero)
      500 MB - 5 GB espacio disco (depende volumen notas)
      Puerto 8000 o custom (configurable)
      Navegador moderno: Chrome, Firefox, Safari, Edge
      Python 3.10+ (si ejecutas sin Docker)
      Setup ultra-rápido: Docker one-liner. 60 segundos a funcionar.
    Instalación con Docker Compose
    Opción 1: Docker Compose (recomendado)
    mkdir -p notediscovery/data && cd notediscovery
curl -O https://raw.githubusercontent.com/gamosoft/NoteDiscovery/main/docker-compose.ghcr.yml
docker compose -f docker-compose.ghcr.yml up -d
    Opción 2: Docker Compose custom
docker compose up -d
    Opción 3: Docker run simple
    mkdir -p ./notediscovery-data
docker run -d \
  --name notediscovery \
  --restart unless-stopped \
  -p 8000:8000 \
  -v ./notediscovery-data:/app/data \
  ghcr.io/gamosoft/notediscovery:latest
    Acceder (setup inicial)
    http://localhost:8000 - Dashboard NoteDiscovery
    Primer uso
      Abre http://localhost:8000
      Verás editor Markdown split-pane limpio
      Click "New Note" para crear primera nota
      Escribe título y contenido
      Auto-save cada 5 segundos (visto en UI)
      ¡Listo! Notas guardadas en ./data/
    Primeros pasos
    1. Crear primera nota
      Click "+ New Note"
      Nombre: "Mi Primera Nota"
      Contenido: escribe Markdown (# Título, **bold**, etc)
      Live preview aparece a la derecha en tiempo real
      Auto-saved
    2. Usar wikilinks (backlinks bidireccionales)
      En nota, escribe: [[Otra Nota]]
      Se crea automático link a esa nota
      En "Otra Nota", verás backlink a primera nota
      Graph view muestra conexión visualmente
    3. Ver grafo de conocimiento
      Menú → "Graph View"
      Visualiza notas como nodos, links como aristas
      Click nodo para navegar a nota
      Zoom, pan, interactivo
    4. Buscar notas (instant full-text)
      Search bar arriba (lupa icon)
      Escribe palabra clave
      Resultados instant en ambos: titulo + contenido
      Cached para velocidad
    5. Star favoritos
      Nota → click ⭐ icon
      Aparece en "Favoritos" panel
      Acceso rápido a notas importantes
    6. Usar LaTeX (ecuaciones matemáticas)
    $$E = mc^2$$
Inline: $E = mc^2$
      Powered by MathJax
      Renderiza automático en preview
    7. Insertar Mermaid diagrams
    ```mermaid
graph TD
  A[Start] --> B[Process]
  B --> C[End]
```
    8. Dibujar sketches (in-app drawing)
      Menu → "+ New Drawing"
      Editor de dibujo aparece (pencil, lines, shapes, color picker)
      Autosave como PNG next to nota
      Link en Markdown para embed
    9. Cambiar tema (Dark/Light mode)
      Settings (engranaje icon) → Theme
      Elige Dark, Light, o custom
      Preferencia guardada
    10. MCP para IA (Claude, Cursor)
      En Claude Desktop config (~/.claude-desktop/claude_desktop_config.json):
    {
  "mcpServers": {
    "notediscovery": {
      "command": "docker",
      "args": [
        "run", "--rm", "-i",
        "-e", "NOTEDISCOVERY_URL=http://host.docker.internal:8000",
        "ghcr.io/gamosoft/notediscovery:latest",
        "python", "-m", "mcp_server"
      ]
    }
  }
}
      Reinicia Claude Desktop
      Claude ahora puede leer tus notas, explorar grafo, encontrar backlinks
    11. Cambiar idioma
      Settings → Language
      Elige español (u otro)
      UI cambia al instante
    Casos de uso
      Segunda cerebro (Zettelkasten): Sistema de notas conectadas. Descubre patrones. Asimilación conocimiento.
      Researchers/scholars: Base de conocimiento de papers, artículos, ideas. Grafo de referencias.
      Developers: Wiki técnica personal. Documentación interna. Recipes, cheat sheets, tutoriales.
      Teams/pequeños equipos: Wiki compartida. Control vía git. Sin SaaS.
      Privacidad-first: Notas nunca leave your server. Cero telemetría. Zero tracking.
    HTTPS con Caddy (producción)
    Caddyfile simple
    notes.tudominio.com {
  reverse_proxy localhost:8000
}
    Acceso remoto seguro
    https://notes.tudominio.com con HTTPS automático
    IMPORTANTE: Proteger con autenticación
    Por defecto, NoteDiscovery NO tiene autenticación (default password: admin). CAMBIAR si expones a red
    Gestión y mantenimiento
    Ver logs
    docker logs -f notediscovery
    Backup de notas (IMPORTANTE)
    cp -r ./data ./data-backup-$(date +%Y%m%d-%H%M%S)
# O con git (repo tu data folder)
cd ./data && git add . && git commit -m "Backup $(date)" && cd ..
    Restore de backup
    docker stop notediscovery
rm -rf ./data
cp -r ./data-backup-YYYYMMDD-hhmmss ./data
docker start notediscovery
    Reiniciar container
    docker compose restart
    Actualizar a versión más reciente
    docker compose pull
docker compose up -d
    Monitorear consumo (ultra-ligero)
    docker stats notediscovery
# Típicamente: 
    Explorar notas (CLI)
    ls -la ./data/
# Ver todas las notas .md
find ./data -name "*.md" | wc -l
# Grep en todas tus notas
grep -r "palabra-clave" ./data/
    Comparativa con alternativas
    vs Obsidian Sync (SaaS)
    NoteDiscovery gana: Gratis, self-hosted, web-based. Obsidian gana: Desktop app, plugins masivos, sincronización E2E.
    vs Notion
    NoteDiscovery gana: Markdown puro, privacidad, grafo. Notion gana: Databases, templates, UI polished, team features.
    vs Roam Research (SaaS)
    NoteDiscovery gana: Self-hosted, gratis, open source. Roam gana: Roam protocol, PKM features, community.
    vs Apple Notes/Google Keep
    NoteDiscovery gana: Backlinks, grafo, Markdown, datos tuyos. Cloud gana: Sync automático, simplicity.
      Mejor para: Knowledge workers que valoran privacidad, ownership, Markdown, y grafo. Segunda cerebro sin suscripción.
    Referencias oficiales
      GitHub Repository - gamosoft/NoteDiscovery
      Official Website - notediscovery.com
      Docker Hub - gamosoft/notediscovery
      Live Demo
      Features Documentation
      MCP Integration Guide
    Apoya el canal GENBYTE
    Suscríbete al canal de YouTube
    Suscríbete a la newsletter semanal
    Invítame a un Ko-fi
    genbyte@proton.me
    Sígueme en mis redes sociales
      Telegram
      Discord
      YouTube
      GitHub
      Blog
      Twitter
Obtener enlace
Facebook
X
Pinterest
Correo electrónico
Otras aplicaciones
Comentarios
Publicar un comentario
      BLOG_CMT_createIframe('https://www.blogger.com/rpc_relay.html');
   (adsbygoogle = window.adsbygoogle || []).push({});
    .post-body a.b-tooltip-container {
      position: relative;
      display: inline-block;
    }
    .post-body a.b-tooltip-container .b-tooltip {
      display: block !important;
      position: absolute;
      top: 100%;
      left: 50%;
      transform: translate(-20%, 1px);
      visibility: hidden;
      opacity: 0;
      z-index: 1;
      transition: opacity 0.2s ease-in-out;
    }
    .post-body a.b-tooltip-container .b-tooltip iframe {
      width: 200px;
      height: 198px;
      max-width: none;
      border: none;
      border-radius: 20px;
      box-shadow: 1px 1px 3px 1px rgba(0, 0, 0, 0.2);
    }
    @media (hover: hover) {
      .post-body a.b-tooltip-container:hover .b-tooltip {
        visibility: visible;
        opacity: 1;
      }
    }
Entradas populares de este blog
Cómo Instalar y configurar SERVIDOR VPN WIREGUARD en MIKROTIK 🔐 #VPN #Wireguard #Mikrotik #RouterOS
Wireguard en Mikrotik Breve Explicación de Wireguard ¿Qué es WireGuard VPN? WireGuard es un nuevo protocolo de VPN. No se trata de un software, sino de un conjunto de instrucciones que permite crear VPNs de forma muy sencilla. Ha sido desarrollada como una alternativa a IPsec, OpenVPN y similares VPNs, pero más rápida y sencilla de usar. En esencia, WireGuard está basado en ideas del protocolo IPsec. WireGuard es una VPN extremadamente simple, pero rápida y moderna que utiliza criptografía de última generación. Su objetivo es ser más rápido, más simple, y más versátil que IPSec, evitando al mismo tiempo el enorme dolor de cabeza (sobre todo en redes con NAT). Pretende ser considerablemente más eficaz que OpenVPN. WireGuard está diseñado como una VPN de propósito general para ejecutarse en interfaces embebidas, apto para muchas circunstancias diferentes. Se ejecuta sobre el protocolo UDP, por lo tanto es considerado un túnel de capa 3. ¿Cómo funciona Wireguard VPN? WireGuard es un proto...
Read more »
Cómo instalar y configurar DSM SYNOLOGY 7.2.2 en PC | Guía completa, instalación, RAID 1, SMB
Instalación y puesta en marcha de Synology DSM 7.2.2 en PC Vídeo ACTUALIZADO, NUEVA VERSIÓN DEL ARC LOADER:  https://youtu.be/LgghogL-UCA https://genbyte.blogspot.com/2025/08/como-convertir-pc-en-synlogy-con-6-tb.html ----- Proceso de instalación y puesta en marcha de sistema operativo DSM Synology versión 7.2.2 en un PC, concretamente un HP 800 G1 EliteDesk. El PC tendrá 3 discos SSD, uno de 120 GB para el S.O. DSM, y otros dos de 240GB cada en RAID 1 para los Datos. Los 3 dicos duros conectados al PC mediante cables SATA. Lo primero que necesitamos es descargar la imagen bootloader ARC, desde el siguiente repositorio de Gothub, también necesitamos Rufus, en este momento, es la versión 4.6. Imagen ARC:  https://github.com/AuxXxilium/arc Imagen usado en el vídeo 1.1.29:  https://github.com/AuxXxilium/arc/releases/tag/1.1.29 Rufus:  https://rufus.ie/es/ Después de descargar la imagen ARC.img, conectamos nuestro primer disco SSD de 120GB por cable o conector SATA-USB y...
Read more »
Cómo INSTALAR y CONFIGURAR OpenVPN en MIKROTIK. Guía completa paso a paso.
Cómo INSTALAR y CONFIGURAR OpenVPN en MIKROTIK. Guía completa paso a paso. Vídeo tutorial paso a paso en Youtube Desarrollo Ilustración: Diagrama RED Creación de Redes (Address) ----------------------------------------------- WAN 192.168.1.0/24 LAN 192.168.88.0/24 VPN 192.168.100.0/24 Creación del Rango VPN ------------------------ 192.168.100.1 - 192.168.100.100 Creación de los Certificados ------------------------------- Los certificados que vamos a crear a continuación tendrán una validez de 10 años; days-valid=3650 Crear certificado CA ---------------------- /certificate add name=CA-tpl country="" state="" locality="" organization="" unit="" common-name="CA" key-size=4096 days-valid=3650 key-usage=crl-sign,key-cert-sign /certificate sign CA-tpl ca-crl-host=127.0.0.1 name="CA" Crear certificado Server -------------------------- /certificate add name=SERVER-tpl country="" state="" locality=...
Read more »
Con la tecnología de Blogger
Genbyte © 2026 | Blogger Google
Aprende casi todo sobre Linux:
Libro Administración de Linux: de 0 a 100
<div style="
  max-width: 420px;
  padding: 24px;
  border-radius: 16px;
  background: linear-gradient(135deg, #0f172a, #1e293b);
  color: #ffffff;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Arial, sans-serif;
  box-shadow: 0 10px 25px rgba(0,0,0,0.2);
">
    🚀 La newsletter de Genbyte
    Recibe contenido sobre tecnología, automatizaciones, IA y tendencias digitales directamente en tu bandeja de entrada.
<a 
  href="https://genbyte.beehiiv.com/subscribe" 
  target="_blank" 
  rel="noopener noreferrer"
  style="
    display: block;
    width: 100%;
    box-sizing: border-box;
    text-align: center;
    padding: 12px 16px;
    background: #38bdf8;
    color: #0f172a;
    text-decoration: none;
    font-weight: 600;
    border-radius: 10px;
  "
>
  Suscribirme gratis
Invítame a un Ko-fi
kofiwidget2.init('Support Me on Ko-fi', '#29abe0', 'W7W79Z4P');kofiwidget2.draw();
Mis Links
.lp-social-container {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  justify-content: center;
  margin: 15px 0;
}
.lp-social-pill {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 10px 16px;
  border-radius: 999px;
  text-decoration: none;
  font-family: system-ui, sans-serif;
  font-size: 14px;
  font-weight: 500;
  color: #fff;
  transition: all 0.25s ease;
}
/* 🎨 Colores optimizados */
.lp-social-pill:nth-child(1) { background: #229ED9; }   /* Telegram */
.lp-social-pill:nth-child(2) { background: #5865F2; }   /* Discord */
.lp-social-pill:nth-child(3) { background: #FF0033; color:#ffffff; }   /* YouTube */
.lp-social-pill:nth-child(4) { background: #24292F; }   /* GitHub */
.lp-social-pill:nth-child(5) { background: #34A853; color:#ffffff; }   /* Blog */
.lp-social-pill:nth-child(6) { background: #1D9BF0; }   /* Twitter */
/* ✨ Hover moderno */
.lp-social-pill:hover {
  transform: translateY(-3px) scale(1.03);
  box-shadow: 0 6px 14px rgba(0,0,0,0.25);
  filter: brightness(1.05);
}
    ✉ Telegram
    💬 Discord
    📽 YouTube
    💻 GitHub
    📄 Blog
    🐦 Twitter
Archivo
julio 20268
junio 202626
mayo 202672
abril 202618
marzo 20267
febrero 20264
enero 20265
diciembre 202516
noviembre 20256
octubre 202510
septiembre 20257
agosto 20256
julio 20252
diciembre 20247
noviembre 20245
octubre 20245
septiembre 20249
agosto 20242
julio 20246
junio 20243
mayo 20243
abril 20245
marzo 20241
febrero 202413
enero 202411
diciembre 20234
agosto 20232
julio 20231
mayo 20232
abril 20234
marzo 20235
febrero 20233
enero 20238
diciembre 20224
agosto 20221
mayo 202211
febrero 20222
enero 20221
agosto 20211
julio 20211
junio 20211
mayo 20211
enero 20213
noviembre 20203
octubre 20201
septiembre 20201
agosto 20202
julio 20202
junio 20202
mayo 20203
abril 20202
marzo 20202
febrero 20202
noviembre 20192
octubre 20193
septiembre 20192
noviembre 20182
octubre 20185
enero 20182
mayo 20171
enero 20172
diciembre 20162
agosto 20161
diciembre 20153
noviembre 20156
octubre 20152
septiembre 20151
enero 20152
diciembre 20141
septiembre 20141
agosto 20142
mayo 20142
marzo 20141
febrero 20141
diciembre 20131
noviembre 20133
octubre 20135
Mostrar más
Mostrar menos
Etiquetas
#AppFest2012
#Bilal #Joomla #CMS #Página #Personal #Blog #Analytics #Google
#CPD
#NAS #SAN #Backup #Backup4all #duplicity #Linux #WindowsServer
#RaspberrPi
#SAI
#Seguridad
#SuperComupter
0x80070643
2fa
acceso red
actualizacion coronavirus
actualización windows
adinistracion
alix
almacenamiento
amazon
amd
android
Antivirus
app web
apps
apu
Arabic
archivos
arranque
autenticación
autenticación segura
backup
backup sd
balanceo
Blogger
bloquea ads
boards
borrar
bot
cam
casos
cctv
certbot
certificado digital
certifidado
Chema Alonso
chrome
ciberdilencuente
cifs
clean
clonezilla
cloudflare
Cloudflare WARP
cmd
cola
comand
comandos
comaprtir
conexion
contagios
container
contenedores
copia
copias seguridad
coronavirus
covid
datos
dd
debian
desintalar docker
desktop
dhcp
diseño
disk
diskpart
disney
Diun
dns
doble factor
docker
docker compose
Dockhand
domain
dominio seguro
Dozzel
elimina
English
equipo
error
error windows
escritorio
escritorio remoto
españa
espia
esxi
exportar
ext
extension
facebook
fallecidos
firewall
format
fotos
French
ghost
gmail
google
grabar pantalla
gratis
Hacker
hamachi
HBO
homelab
http://youtu.be/yRGn63y7bP4
https
IFTTT
impresión
imprimir
Instagram
instalar
inventario
inventory
iptv
iptv legal
iso
Jackett
Joomla
KB5034441
lan
letscrypt
lineageos
Linux
local
mac
malware
maquinasvirtuales
microfono
mikrotik
monitoreo
monitorizar
motioneye
móviles
Multilanguage
multiplataforna.
multisesion
multiusuario
nas
net
netflix
netuse
ng
nmap
no exportable
ntfs
nube
ocs
oidc
onedrive
openmediavault
opensource
openvpn
owncloud
p2p
pantallazo
partition
passkeys
password
pendrive
pfsense
pfsesne
phishing
pi
pihole
plex
pocket id
port
portainer
portal cautivo
prescindir windows
prime
privada
Prowlarr
Proxy
prunemate
Radarr
raid
rakuten
RaspberrPi
raspberry
raspberry pi
raspbian
raspeberry
rdp
reagentc /enable
recuperados
red
remota
robocpy
root
rpi
rpimonitor
screenrecord
sd
security
Seguridad
Seguridad Informática
server
servidor casero
servidor dns
share
sistema
sistema operativo
sistemas
smarttv
smb
smtp
so
Sonarr
Spanish
ssh
ssl
storage
superuser
system
tailscale
tdt
telegram
terminal
tls
torrents
Truecrypt
tv
tv box
tv gratis
tv legal
typosquatting
ubuntu
update
usb
usb booteable
use
user
usuario
usuarios
vbox
vigilancia
vincular
virus
vlan
vmware
vpn
vpn segura
wan
web
webcam
windows
windows 10
Windows7
wordpress
xiaomi
Mostrar más
Mostrar menos
Denunciar abuso
    document.addEventListener('DOMContentLoaded', function(event) {
      window.cookieChoices && cookieChoices.showCookieConsentBar && cookieChoices.showCookieConsentBar(
          (window.cookieOptions && cookieOptions.msg) || 'Este sitio utiliza cookies de Google para prestar sus servicios y para analizar su tr\xe1fico. Tu direcci\xf3n IP y user-agent se comparten con Google, junto con las m\xe9tricas de rendimiento y de seguridad, para garantizar la calidad del servicio, generar estad\xedsticas de uso y detectar y solucionar abusos.',
          (window.cookieOptions && cookieOptions.close) || 'Entendido',
          (window.cookieOptions && cookieOptions.learn) || 'M\xe1s informaci\xf3n',
          (window.cookieOptions && cookieOptions.link) || 'https://www.blogger.com/go/blogspot-cookies');
    });
window['__wavt'] = 'AEUoTZqGnLwAnT8lq7Efygzq_IlR:1783519417575';_WidgetManager._Init('//www.blogger.com/rearrange?blogID\x3d8219365441889466865','//genbyte.blogspot.com/2026/07/como-instalar-notediscovery-en-docker.html','8219365441889466865');
_WidgetManager._SetDataContext([{'name': 'blog', 'data': {'blogId': '8219365441889466865', 'title': 'Genbyte', 'url': 'https://genbyte.blogspot.com/2026/07/como-instalar-notediscovery-en-docker.html', 'canonicalUrl': 'https://genbyte.blogspot.com/2026/07/como-instalar-notediscovery-en-docker.html', 'homepageUrl': 'https://genbyte.blogspot.com/', 'searchUrl': 'https://genbyte.blogspot.com/search', 'canonicalHomepageUrl': 'https://genbyte.blogspot.com/', 'blogspotFaviconUrl': 'https://genbyte.blogspot.com/favicon.ico', 'bloggerUrl': 'https://www.blogger.com', 'hasCustomDomain': false, 'httpsEnabled': true, 'enabledCommentProfileImages': true, 'gPlusViewType': 'FILTERED_POSTMOD', 'adultContent': false, 'analyticsAccountNumber': '', 'encoding': 'UTF-8', 'locale': 'es', 'localeUnderscoreDelimited': 'es', 'languageDirection': 'ltr', 'isPrivate': false, 'isMobile': false, 'isMobileRequest': false, 'mobileClass': '', 'isPrivateBlog': false, 'isDynamicViewsAvailable': true, 'feedLinks': '\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22Genbyte - Atom\x22 href\x3d\x22https://genbyte.blogspot.com/feeds/posts/default\x22 /\x3e\n\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/rss+xml\x22 title\x3d\x22Genbyte - RSS\x22 href\x3d\x22https://genbyte.blogspot.com/feeds/posts/default?alt\x3drss\x22 /\x3e\n\x3clink rel\x3d\x22service.post\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22Genbyte - Atom\x22 href\x3d\x22https://www.blogger.com/feeds/8219365441889466865/posts/default\x22 /\x3e\n\n\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22Genbyte - Atom\x22 href\x3d\x22https://genbyte.blogspot.com/feeds/5369295723767392150/comments/default\x22 /\x3e\n', 'meTag': '', 'adsenseClientId': 'ca-pub-5584594928588539', 'adsenseHostId': 'ca-host-pub-1556223355139109', 'adsenseHasAds': true, 'adsenseAutoAds': true, 'boqCommentIframeForm': true, 'loginRedirectParam': '', 'isGoogleEverywhereLinkTooltipEnabled': true, 'view': '', 'dynamicViewsCommentsSrc': '//www.blogblog.com/dynamicviews/4224c15c4e7c9321/js/comments.js', 'dynamicViewsScriptSrc': '//www.blogblog.com/dynamicviews/a8c62dcffd0094e0', 'plusOneApiSrc': 'https://apis.google.com/js/platform.js', 'disableGComments': true, 'interstitialAccepted': false, 'sharing': {'platforms': [{'name': 'Obtener enlace', 'key': 'link', 'shareMessage': 'Obtener enlace', 'target': ''}, {'name': 'Facebook', 'key': 'facebook', 'shareMessage': 'Compartir en Facebook', 'target': 'facebook'}, {'name': 'Escribe un blog', 'key': 'blogThis', 'shareMessage': 'Escribe un blog', 'target': 'blog'}, {'name': 'X', 'key': 'twitter', 'shareMessage': 'Compartir en X', 'target': 'twitter'}, {'name': 'Pinterest', 'key': 'pinterest', 'shareMessage': 'Compartir en Pinterest', 'target': 'pinterest'}, {'name': 'Correo electr\xf3nico', 'key': 'email', 'shareMessage': 'Correo electr\xf3nico', 'target': 'email'}], 'disableGooglePlus': true, 'googlePlusShareButtonWidth': 0, 'googlePlusBootstrap': '\x3cscript type\x3d\x22text/javascript\x22\x3ewindow.___gcfg \x3d {\x27lang\x27: \x27es\x27};\x3c/script\x3e'}, 'hasCustomJumpLinkMessage': true, 'jumpLinkMessage': 'Read more \xbb', 'pageType': 'item', 'postId': '5369295723767392150', 'postImageThumbnailUrl': 'https://blogger.googleusercontent.com/img/a/AVvXsEhbPGv8wgBFqzoNHIseXbVQ4I-2eHUlCCRYJcGhhEHNC-b3O51a-fKenAjngZ1LV1YbAbw0aJyTLIKZhmX8AJQCqvV6a_Qzi-l0OrTZr2Pr8SkOD6O034-WJCbotpAJPaVT0h2f1kSu6julIJHqR5eZqUiLPM0rO0SSZnCosqL-O0oWy4zGZHOTyFNOjjU\x3ds72-c', 'postImageUrl': 'https://blogger.googleusercontent.com/img/a/AVvXsEhbPGv8wgBFqzoNHIseXbVQ4I-2eHUlCCRYJcGhhEHNC-b3O51a-fKenAjngZ1LV1YbAbw0aJyTLIKZhmX8AJQCqvV6a_Qzi-l0OrTZr2Pr8SkOD6O034-WJCbotpAJPaVT0h2f1kSu6julIJHqR5eZqUiLPM0rO0SSZnCosqL-O0oWy4zGZHOTyFNOjjU', 'pageName': 'C\xf3mo instalar NoteDiscovery en Docker - Base de conocimiento autohospedada en Docker', 'pageTitle': 'Genbyte: C\xf3mo instalar NoteDiscovery en Docker - Base de conocimiento autohospedada en Docker'}}, {'name': 'features', 'data': {}}, {'name': 'messages', 'data': {'edit': 'Editar', 'linkCopiedToClipboard': 'El enlace se ha copiado en el Portapapeles.', 'ok': 'Aceptar', 'postLink': 'Enlace de la entrada'}}, {'name': 'template', 'data': {'name': 'custom', 'localizedName': 'Personalizado', 'isResponsive': true, 'isAlternateRendering': false, 'isCustom': true}}, {'name': 'view', 'data': {'classic': {'name': 'classic', 'url': '?view\x3dclassic'}, 'flipcard': {'name': 'flipcard', 'url': '?view\x3dflipcard'}, 'magazine': {'name': 'magazine', 'url': '?view\x3dmagazine'}, 'mosaic': {'name': 'mosaic', 'url': '?view\x3dmosaic'}, 'sidebar': {'name': 'sidebar', 'url': '?view\x3dsidebar'}, 'snapshot': {'name': 'snapshot', 'url': '?view\x3dsnapshot'}, 'timeslide': {'name': 'timeslide', 'url': '?view\x3dtimeslide'}, 'isMobile': false, 'title': 'C\xf3mo instalar NoteDiscovery en Docker - Base de conocimiento autohospedada en Docker', 'description': '              NoteDiscovery | Knowledge Base | Docker      NoteDiscovery: Base de conocimiento autohospedada en Docker (alternativa Obsidian...', 'featuredImage': 'https://blogger.googleusercontent.com/img/a/AVvXsEhbPGv8wgBFqzoNHIseXbVQ4I-2eHUlCCRYJcGhhEHNC-b3O51a-fKenAjngZ1LV1YbAbw0aJyTLIKZhmX8AJQCqvV6a_Qzi-l0OrTZr2Pr8SkOD6O034-WJCbotpAJPaVT0h2f1kSu6julIJHqR5eZqUiLPM0rO0SSZnCosqL-O0oWy4zGZHOTyFNOjjU', 'url': 'https://genbyte.blogspot.com/2026/07/como-instalar-notediscovery-en-docker.html', 'type': 'item', 'isSingleItem': true, 'isMultipleItems': false, 'isError': false, 'isPage': false, 'isPost': true, 'isHomepage': false, 'isArchive': false, 'isLabelSearch': false, 'postId': 5369295723767392150}}, {'name': 'widgets', 'data': [{'title': 'Buscar este blog', 'type': 'BlogSearch', 'sectionId': 'search_top', 'id': 'BlogSearch1'}, {'title': 'Genbyte (cabecera)', 'type': 'Header', 'sectionId': 'header', 'id': 'Header1'}, {'title': '', 'type': 'PageList', 'sectionId': 'page_list_top', 'id': 'PageList1'}, {'type': 'AdSense', 'sectionId': 'ads', 'id': 'AdSense1'}, {'type': 'AdSense', 'sectionId': 'ads', 'id': 'AdSense2'}, {'title': 'Entradas del blog', 'type': 'Blog', 'sectionId': 'page_body', 'id': 'Blog1', 'posts': [{'id': '5369295723767392150', 'title': 'C\xf3mo instalar NoteDiscovery en Docker - Base de conocimiento autohospedada en Docker', 'featuredImage': 'https://blogger.googleusercontent.com/img/a/AVvXsEhbPGv8wgBFqzoNHIseXbVQ4I-2eHUlCCRYJcGhhEHNC-b3O51a-fKenAjngZ1LV1YbAbw0aJyTLIKZhmX8AJQCqvV6a_Qzi-l0OrTZr2Pr8SkOD6O034-WJCbotpAJPaVT0h2f1kSu6julIJHqR5eZqUiLPM0rO0SSZnCosqL-O0oWy4zGZHOTyFNOjjU', 'showInlineAds': true}], 'headerByline': {'regionName': 'header1', 'items': [{'name': 'share', 'label': ''}]}, 'footerBylines': [{'regionName': 'footer1', 'items': [{'name': 'comments', 'label': 'comments'}, {'name': 'icons', 'label': ''}]}, {'regionName': 'footer2', 'items': [{'name': 'labels', 'label': ''}]}, {'regionName': 'footer3', 'items': [{'name': 'location', 'label': 'Location:'}]}], 'allBylineItems': [{'name': 'share', 'label': ''}, {'name': 'comments', 'label': 'comments'}, {'name': 'icons', 'label': ''}, {'name': 'labels', 'label': ''}, {'name': 'location', 'label': 'Location:'}]}, {'title': '', 'type': 'PopularPosts', 'sectionId': 'page_body', 'id': 'PopularPosts1', 'posts': [{'title': 'C\xf3mo Instalar y configurar SERVIDOR VPN WIREGUARD en MIKROTIK \ud83d\udd10 #VPN #Wireguard #Mikrotik #RouterOS', 'id': 7806756629556397861}, {'title': 'C\xf3mo instalar y configurar DSM SYNOLOGY 7.2.2 en PC | Gu\xeda completa, instalaci\xf3n, RAID 1, SMB', 'id': 6323457506488490841}, {'title': 'C\xf3mo INSTALAR y CONFIGURAR OpenVPN en MIKROTIK. Gu\xeda completa paso a paso.', 'id': 3276948939221682320}]}, {'type': 'Attribution', 'sectionId': 'footer', 'id': 'Attribution1'}, {'title': 'Aprende casi todo sobre Linux:', 'type': 'HTML', 'sectionId': 'sidebar_bottom', 'id': 'HTML4'}, {'title': '', 'type': 'HTML', 'sectionId': 'sidebar_bottom', 'id': 'HTML3'}, {'title': 'Inv\xedtame a un Ko-fi', 'type': 'HTML', 'sectionId': 'sidebar_bottom', 'id': 'HTML1'}, {'title': 'Mis Links', 'type': 'HTML', 'sectionId': 'sidebar_bottom', 'id': 'HTML2'}, {'title': '', 'type': 'BlogArchive', 'sectionId': 'sidebar_bottom', 'id': 'BlogArchive1'}, {'title': 'Etiquetas', 'type': 'Label', 'sectionId': 'sidebar_bottom', 'id': 'Label1'}, {'title': '', 'type': 'ReportAbuse', 'sectionId': 'sidebar_bottom', 'id': 'ReportAbuse1'}]}]);
_WidgetManager._RegisterWidget('_BlogSearchView', new _WidgetInfo('BlogSearch1', 'search_top', document.getElementById('BlogSearch1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HeaderView', new _WidgetInfo('Header1', 'header', document.getElementById('Header1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_PageListView', new _WidgetInfo('PageList1', 'page_list_top', document.getElementById('PageList1'), {'title': '', 'links': [{'isCurrentPage': false, 'href': 'http://genbyte.blogspot.com/', 'title': 'Inicio'}, {'isCurrentPage': false, 'href': 'https://www.youtube.com/@genbyte', 'title': 'Mi canal Youtube'}, {'isCurrentPage': false, 'href': 'https://genbyte.blogspot.com/p/newsletter.html', 'id': '2370245159635941192', 'title': 'Newsletter'}], 'mobile': false, 'showPlaceholder': true, 'hasCurrentPage': false}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_AdSenseView', new _WidgetInfo('AdSense1', 'ads', document.getElementById('AdSense1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_AdSenseView', new _WidgetInfo('AdSense2', 'ads', document.getElementById('AdSense2'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_BlogView', new _WidgetInfo('Blog1', 'page_body', document.getElementById('Blog1'), {'cmtInteractionsEnabled': false, 'lightboxEnabled': true, 'lightboxModuleUrl': 'https://www.blogger.com/static/v1/jsbin/3745941268-lbx__es.js', 'lightboxCssUrl': 'https://www.blogger.com/static/v1/v-css/828616780-lightbox_bundle.css'}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_PopularPostsView', new _WidgetInfo('PopularPosts1', 'page_body', document.getElementById('PopularPosts1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_AttributionView', new _WidgetInfo('Attribution1', 'footer', document.getElementById('Attribution1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HTMLView', new _WidgetInfo('HTML4', 'sidebar_bottom', document.getElementById('HTML4'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HTMLView', new _WidgetInfo('HTML3', 'sidebar_bottom', document.getElementById('HTML3'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HTMLView', new _WidgetInfo('HTML1', 'sidebar_bottom', document.getElementById('HTML1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HTMLView', new _WidgetInfo('HTML2', 'sidebar_bottom', document.getElementById('HTML2'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_BlogArchiveView', new _WidgetInfo('BlogArchive1', 'sidebar_bottom', document.getElementById('BlogArchive1'), {'languageDirection': 'ltr', 'loadingMessage': 'Cargando\x26hellip;'}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_LabelView', new _WidgetInfo('Label1', 'sidebar_bottom', document.getElementById('Label1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_ReportAbuseView', new _WidgetInfo('ReportAbuse1', 'sidebar_bottom', document.getElementById('ReportAbuse1'), {}, 'displayModeFull'));