                              1 ;--------------------------------------------------------
                              2 ; File Created by SDCC : free open source ANSI-C Compiler
                              3 ; Version 2.8.0 #5117 (Mar 23 2008) (MINGW32)
                              4 ; This file was generated Sun Mar 18 12:42:07 2012
                              5 ;--------------------------------------------------------
                              6 	.module fb_rs232
                              7 	.optsdcc -mmcs51 --model-small
                              8 	
                              9 ;--------------------------------------------------------
                             10 ; Public variables in this module
                             11 ;--------------------------------------------------------
                             12 	.globl _P3_1
                             13 	.globl _P3_0
                             14 	.globl _P1_7
                             15 	.globl _P1_6
                             16 	.globl _P1_5
                             17 	.globl _P1_4
                             18 	.globl _P1_3
                             19 	.globl _P1_2
                             20 	.globl _P1_1
                             21 	.globl _P1_0
                             22 	.globl _P0_7
                             23 	.globl _P0_6
                             24 	.globl _P0_5
                             25 	.globl _P0_4
                             26 	.globl _P0_3
                             27 	.globl _P0_2
                             28 	.globl _P0_1
                             29 	.globl _P0_0
                             30 	.globl _I2CON_0
                             31 	.globl _I2CON_2
                             32 	.globl _I2CON_3
                             33 	.globl _I2CON_4
                             34 	.globl _I2CON_5
                             35 	.globl _I2CON_6
                             36 	.globl _SCON_7
                             37 	.globl _SCON_6
                             38 	.globl _SCON_5
                             39 	.globl _SCON_4
                             40 	.globl _SCON_3
                             41 	.globl _SCON_2
                             42 	.globl _SCON_1
                             43 	.globl _SCON_0
                             44 	.globl _IP0_0
                             45 	.globl _IP0_1
                             46 	.globl _IP0_2
                             47 	.globl _IP0_3
                             48 	.globl _IP0_4
                             49 	.globl _IP0_5
                             50 	.globl _IP0_6
                             51 	.globl _IP1_0
                             52 	.globl _IP1_1
                             53 	.globl _IP1_2
                             54 	.globl _IP1_6
                             55 	.globl _IEN1_0
                             56 	.globl _IEN1_1
                             57 	.globl _IEN1_2
                             58 	.globl _IEN0_0
                             59 	.globl _IEN0_1
                             60 	.globl _IEN0_2
                             61 	.globl _IEN0_3
                             62 	.globl _IEN0_4
                             63 	.globl _IEN0_5
                             64 	.globl _IEN0_6
                             65 	.globl _IEN0_7
                             66 	.globl _TCON_0
                             67 	.globl _TCON_1
                             68 	.globl _TCON_2
                             69 	.globl _TCON_3
                             70 	.globl _TCON_4
                             71 	.globl _TCON_5
                             72 	.globl _TCON_6
                             73 	.globl _TCON_7
                             74 	.globl _PSW_7
                             75 	.globl _PSW_6
                             76 	.globl _PSW_5
                             77 	.globl _PSW_4
                             78 	.globl _PSW_3
                             79 	.globl _PSW_2
                             80 	.globl _PSW_1
                             81 	.globl _PSW_0
                             82 	.globl _IEN1
                             83 	.globl _IP0H
                             84 	.globl _WFEED2
                             85 	.globl _WFEED1
                             86 	.globl _WDL
                             87 	.globl _WDCON
                             88 	.globl _TRIM
                             89 	.globl _TAMOD
                             90 	.globl _SSTAT
                             91 	.globl _RTCL
                             92 	.globl _RTCH
                             93 	.globl _RTCCON
                             94 	.globl _RSTSRC
                             95 	.globl _PT0AD
                             96 	.globl _PCONA
                             97 	.globl _P3M2
                             98 	.globl _P3M1
                             99 	.globl _P1M2
                            100 	.globl _P1M1
                            101 	.globl _P0M2
                            102 	.globl _P0M1
                            103 	.globl _KBPATN
                            104 	.globl _KBMASK
                            105 	.globl _KBCON
                            106 	.globl _IP1H
                            107 	.globl _IP1
                            108 	.globl _I2STAT
                            109 	.globl _I2SCLL
                            110 	.globl _I2SCLH
                            111 	.globl _I2DAT
                            112 	.globl _I2CON
                            113 	.globl _I2ADR
                            114 	.globl _FMDATA
                            115 	.globl _FMCON
                            116 	.globl _FMADRL
                            117 	.globl _FMADRH
                            118 	.globl _DIVM
                            119 	.globl _CMP2
                            120 	.globl _CMP1
                            121 	.globl _BRGCON
                            122 	.globl _BRGR1
                            123 	.globl _BRGR0
                            124 	.globl _SADEN
                            125 	.globl _SADDR
                            126 	.globl _AUXR1
                            127 	.globl _SBUF
                            128 	.globl _SCON
                            129 	.globl _IP0
                            130 	.globl _IEN0
                            131 	.globl _TH1
                            132 	.globl _TH0
                            133 	.globl _TL1
                            134 	.globl _TL0
                            135 	.globl _TMOD
                            136 	.globl _TCON
                            137 	.globl _PCON
                            138 	.globl _DPH
                            139 	.globl _DPL
                            140 	.globl _SP
                            141 	.globl _B
                            142 	.globl _ACC
                            143 	.globl _PSW
                            144 	.globl _P3
                            145 	.globl _P1
                            146 	.globl _P0
                            147 	.globl _rs_init
                            148 	.globl _rs_send_dec
                            149 	.globl _rs_send_s
                            150 	.globl _rs_send_hex_i
                            151 	.globl _rs_send_hex
                            152 	.globl _rs_send
                            153 ;--------------------------------------------------------
                            154 ; special function registers
                            155 ;--------------------------------------------------------
                            156 	.area RSEG    (DATA)
                    0080    157 _P0	=	0x0080
                    0090    158 _P1	=	0x0090
                    00B0    159 _P3	=	0x00b0
                    00D0    160 _PSW	=	0x00d0
                    00E0    161 _ACC	=	0x00e0
                    00F0    162 _B	=	0x00f0
                    0081    163 _SP	=	0x0081
                    0082    164 _DPL	=	0x0082
                    0083    165 _DPH	=	0x0083
                    0087    166 _PCON	=	0x0087
                    0088    167 _TCON	=	0x0088
                    0089    168 _TMOD	=	0x0089
                    008A    169 _TL0	=	0x008a
                    008B    170 _TL1	=	0x008b
                    008C    171 _TH0	=	0x008c
                    008D    172 _TH1	=	0x008d
                    00A8    173 _IEN0	=	0x00a8
                    00B8    174 _IP0	=	0x00b8
                    0098    175 _SCON	=	0x0098
                    0099    176 _SBUF	=	0x0099
                    00A2    177 _AUXR1	=	0x00a2
                    00A9    178 _SADDR	=	0x00a9
                    00B9    179 _SADEN	=	0x00b9
                    00BE    180 _BRGR0	=	0x00be
                    00BF    181 _BRGR1	=	0x00bf
                    00BD    182 _BRGCON	=	0x00bd
                    00AC    183 _CMP1	=	0x00ac
                    00AD    184 _CMP2	=	0x00ad
                    0095    185 _DIVM	=	0x0095
                    00E7    186 _FMADRH	=	0x00e7
                    00E6    187 _FMADRL	=	0x00e6
                    00E4    188 _FMCON	=	0x00e4
                    00E5    189 _FMDATA	=	0x00e5
                    00DB    190 _I2ADR	=	0x00db
                    00D8    191 _I2CON	=	0x00d8
                    00DA    192 _I2DAT	=	0x00da
                    00DD    193 _I2SCLH	=	0x00dd
                    00DC    194 _I2SCLL	=	0x00dc
                    00D9    195 _I2STAT	=	0x00d9
                    00F8    196 _IP1	=	0x00f8
                    00F7    197 _IP1H	=	0x00f7
                    0094    198 _KBCON	=	0x0094
                    0086    199 _KBMASK	=	0x0086
                    0093    200 _KBPATN	=	0x0093
                    0084    201 _P0M1	=	0x0084
                    0085    202 _P0M2	=	0x0085
                    0091    203 _P1M1	=	0x0091
                    0092    204 _P1M2	=	0x0092
                    00B1    205 _P3M1	=	0x00b1
                    00B2    206 _P3M2	=	0x00b2
                    00B5    207 _PCONA	=	0x00b5
                    00F6    208 _PT0AD	=	0x00f6
                    00DF    209 _RSTSRC	=	0x00df
                    00D1    210 _RTCCON	=	0x00d1
                    00D2    211 _RTCH	=	0x00d2
                    00D3    212 _RTCL	=	0x00d3
                    00BA    213 _SSTAT	=	0x00ba
                    008F    214 _TAMOD	=	0x008f
                    0096    215 _TRIM	=	0x0096
                    00A7    216 _WDCON	=	0x00a7
                    00C1    217 _WDL	=	0x00c1
                    00C2    218 _WFEED1	=	0x00c2
                    00C3    219 _WFEED2	=	0x00c3
                    00B7    220 _IP0H	=	0x00b7
                    00E8    221 _IEN1	=	0x00e8
                            222 ;--------------------------------------------------------
                            223 ; special function bits
                            224 ;--------------------------------------------------------
                            225 	.area RSEG    (DATA)
                    00D0    226 _PSW_0	=	0x00d0
                    00D1    227 _PSW_1	=	0x00d1
                    00D2    228 _PSW_2	=	0x00d2
                    00D3    229 _PSW_3	=	0x00d3
                    00D4    230 _PSW_4	=	0x00d4
                    00D5    231 _PSW_5	=	0x00d5
                    00D6    232 _PSW_6	=	0x00d6
                    00D7    233 _PSW_7	=	0x00d7
                    008F    234 _TCON_7	=	0x008f
                    008E    235 _TCON_6	=	0x008e
                    008D    236 _TCON_5	=	0x008d
                    008C    237 _TCON_4	=	0x008c
                    008B    238 _TCON_3	=	0x008b
                    008A    239 _TCON_2	=	0x008a
                    0089    240 _TCON_1	=	0x0089
                    0088    241 _TCON_0	=	0x0088
                    00AF    242 _IEN0_7	=	0x00af
                    00AE    243 _IEN0_6	=	0x00ae
                    00AD    244 _IEN0_5	=	0x00ad
                    00AC    245 _IEN0_4	=	0x00ac
                    00AB    246 _IEN0_3	=	0x00ab
                    00AA    247 _IEN0_2	=	0x00aa
                    00A9    248 _IEN0_1	=	0x00a9
                    00A8    249 _IEN0_0	=	0x00a8
                    00EA    250 _IEN1_2	=	0x00ea
                    00E9    251 _IEN1_1	=	0x00e9
                    00E8    252 _IEN1_0	=	0x00e8
                    00FE    253 _IP1_6	=	0x00fe
                    00FA    254 _IP1_2	=	0x00fa
                    00F9    255 _IP1_1	=	0x00f9
                    00F8    256 _IP1_0	=	0x00f8
                    00BE    257 _IP0_6	=	0x00be
                    00BD    258 _IP0_5	=	0x00bd
                    00BC    259 _IP0_4	=	0x00bc
                    00BB    260 _IP0_3	=	0x00bb
                    00BA    261 _IP0_2	=	0x00ba
                    00B9    262 _IP0_1	=	0x00b9
                    00B8    263 _IP0_0	=	0x00b8
                    0098    264 _SCON_0	=	0x0098
                    0099    265 _SCON_1	=	0x0099
                    009A    266 _SCON_2	=	0x009a
                    009B    267 _SCON_3	=	0x009b
                    009C    268 _SCON_4	=	0x009c
                    009D    269 _SCON_5	=	0x009d
                    009E    270 _SCON_6	=	0x009e
                    009F    271 _SCON_7	=	0x009f
                    00DE    272 _I2CON_6	=	0x00de
                    00DD    273 _I2CON_5	=	0x00dd
                    00DC    274 _I2CON_4	=	0x00dc
                    00DB    275 _I2CON_3	=	0x00db
                    00DA    276 _I2CON_2	=	0x00da
                    00D8    277 _I2CON_0	=	0x00d8
                    0080    278 _P0_0	=	0x0080
                    0081    279 _P0_1	=	0x0081
                    0082    280 _P0_2	=	0x0082
                    0083    281 _P0_3	=	0x0083
                    0084    282 _P0_4	=	0x0084
                    0085    283 _P0_5	=	0x0085
                    0086    284 _P0_6	=	0x0086
                    0087    285 _P0_7	=	0x0087
                    0090    286 _P1_0	=	0x0090
                    0091    287 _P1_1	=	0x0091
                    0092    288 _P1_2	=	0x0092
                    0093    289 _P1_3	=	0x0093
                    0094    290 _P1_4	=	0x0094
                    0095    291 _P1_5	=	0x0095
                    0096    292 _P1_6	=	0x0096
                    0097    293 _P1_7	=	0x0097
                    00B0    294 _P3_0	=	0x00b0
                    00B1    295 _P3_1	=	0x00b1
                            296 ;--------------------------------------------------------
                            297 ; overlayable register banks
                            298 ;--------------------------------------------------------
                            299 	.area REG_BANK_0	(REL,OVR,DATA)
   0000                     300 	.ds 8
                            301 ;--------------------------------------------------------
                            302 ; internal ram data
                            303 ;--------------------------------------------------------
                            304 	.area DSEG    (DATA)
                            305 ;--------------------------------------------------------
                            306 ; overlayable items in internal ram 
                            307 ;--------------------------------------------------------
                            308 	.area OSEG    (OVR,DATA)
                            309 ;--------------------------------------------------------
                            310 ; indirectly addressable internal ram data
                            311 ;--------------------------------------------------------
                            312 	.area ISEG    (DATA)
                            313 ;--------------------------------------------------------
                            314 ; absolute internal ram data
                            315 ;--------------------------------------------------------
                            316 	.area IABS    (ABS,DATA)
                            317 	.area IABS    (ABS,DATA)
                            318 ;--------------------------------------------------------
                            319 ; bit data
                            320 ;--------------------------------------------------------
                            321 	.area BSEG    (BIT)
                            322 ;--------------------------------------------------------
                            323 ; paged external ram data
                            324 ;--------------------------------------------------------
                            325 	.area PSEG    (PAG,XDATA)
                            326 ;--------------------------------------------------------
                            327 ; external ram data
                            328 ;--------------------------------------------------------
                            329 	.area XSEG    (XDATA)
                            330 ;--------------------------------------------------------
                            331 ; absolute external ram data
                            332 ;--------------------------------------------------------
                            333 	.area XABS    (ABS,XDATA)
                            334 ;--------------------------------------------------------
                            335 ; external initialized ram data
                            336 ;--------------------------------------------------------
                            337 	.area XISEG   (XDATA)
                            338 	.area HOME    (CODE)
                            339 	.area GSINIT0 (CODE)
                            340 	.area GSINIT1 (CODE)
                            341 	.area GSINIT2 (CODE)
                            342 	.area GSINIT3 (CODE)
                            343 	.area GSINIT4 (CODE)
                            344 	.area GSINIT5 (CODE)
                            345 	.area GSINIT  (CODE)
                            346 	.area GSFINAL (CODE)
                            347 	.area CSEG    (CODE)
                            348 ;--------------------------------------------------------
                            349 ; global & static initialisations
                            350 ;--------------------------------------------------------
                            351 	.area HOME    (CODE)
                            352 	.area GSINIT  (CODE)
                            353 	.area GSFINAL (CODE)
                            354 	.area GSINIT  (CODE)
                            355 ;--------------------------------------------------------
                            356 ; Home
                            357 ;--------------------------------------------------------
                            358 	.area HOME    (CODE)
                            359 	.area HOME    (CODE)
                            360 ;--------------------------------------------------------
                            361 ; code
                            362 ;--------------------------------------------------------
                            363 	.area CSEG    (CODE)
                            364 ;------------------------------------------------------------
                            365 ;Allocation info for local variables in function 'rs_init'
                            366 ;------------------------------------------------------------
                            367 ;------------------------------------------------------------
                            368 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:22: void rs_init( void)
                            369 ;	-----------------------------------------
                            370 ;	 function rs_init
                            371 ;	-----------------------------------------
   0F6B                     372 _rs_init:
                    0002    373 	ar2 = 0x02
                    0003    374 	ar3 = 0x03
                    0004    375 	ar4 = 0x04
                    0005    376 	ar5 = 0x05
                    0006    377 	ar6 = 0x06
                    0007    378 	ar7 = 0x07
                    0000    379 	ar0 = 0x00
                    0001    380 	ar1 = 0x01
                            381 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:48: BRGCON&=0xFE;	// Baudrate Generator stoppen
   0F6B 53 BD FE            382 	anl	_BRGCON,#0xFE
                            383 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:49: P1M1&=0xFC;		// RX und TX auf bidirectional setzen
   0F6E 53 91 FC            384 	anl	_P1M1,#0xFC
                            385 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:50: P1M2&=0xFC;
   0F71 53 92 FC            386 	anl	_P1M2,#0xFC
                            387 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:51: SCON=0x50;		// Mode 1, receive enable
   0F74 75 98 50            388 	mov	_SCON,#0x50
                            389 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:52: SSTAT|=0xE0;	// TI wird am Ende des Stopbits gesetzt und Interrupt nur bei RX und double TX buffer an
   0F77 43 BA E0            390 	orl	_SSTAT,#0xE0
                            391 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:53: BRGCON|=0x02;	// Baudrate Generator verwenden aber noch gestoppt
   0F7A 43 BD 02            392 	orl	_BRGCON,#0x02
                            393 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:54: BRGR1=0x2F;//brg>>8;	// Baudrate = cclk/((BRGR1,BRGR0)+16)
   0F7D 75 BF 2F            394 	mov	_BRGR1,#0x2F
                            395 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:55: BRGR0=0xF0;//brg;
   0F80 75 BE F0            396 	mov	_BRGR0,#0xF0
                            397 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:56: BRGCON|=0x01;	// Baudrate Generator starten
   0F83 43 BD 01            398 	orl	_BRGCON,#0x01
                            399 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:57: TI=1;
   0F86 D2 99               400 	setb	_SCON_1
   0F88 22                  401 	ret
                            402 ;------------------------------------------------------------
                            403 ;Allocation info for local variables in function 'rs_send_dec'
                            404 ;------------------------------------------------------------
                            405 ;wert                      Allocated to registers r2 r3 
                            406 ;------------------------------------------------------------
                            407 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:85: void rs_send_dec(unsigned int wert)
                            408 ;	-----------------------------------------
                            409 ;	 function rs_send_dec
                            410 ;	-----------------------------------------
   0F89                     411 _rs_send_dec:
   0F89 AA 82               412 	mov	r2,dpl
                            413 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:145: TI=0;
   0F8B C2 99               414 	clr	_SCON_1
                            415 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:146: SBUF=wert+48;
   0F8D 74 30               416 	mov	a,#0x30
   0F8F 2A                  417 	add	a,r2
   0F90 F5 99               418 	mov	_SBUF,a
   0F92 22                  419 	ret
                            420 ;------------------------------------------------------------
                            421 ;Allocation info for local variables in function 'rs_send_s'
                            422 ;------------------------------------------------------------
                            423 ;s                         Allocated to registers r2 r3 r4 
                            424 ;n                         Allocated to registers r5 
                            425 ;------------------------------------------------------------
                            426 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:160: void rs_send_s(unsigned char *s)
                            427 ;	-----------------------------------------
                            428 ;	 function rs_send_s
                            429 ;	-----------------------------------------
   0F93                     430 _rs_send_s:
   0F93 AA 82               431 	mov	r2,dpl
   0F95 AB 83               432 	mov	r3,dph
   0F97 AC F0               433 	mov	r4,b
                            434 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:163: while (s[n]!=0)
   0F99 7D 00               435 	mov	r5,#0x00
   0F9B                     436 00111$:
   0F9B ED                  437 	mov	a,r5
   0F9C 2A                  438 	add	a,r2
   0F9D FE                  439 	mov	r6,a
   0F9E E4                  440 	clr	a
   0F9F 3B                  441 	addc	a,r3
   0FA0 FF                  442 	mov	r7,a
   0FA1 8C 00               443 	mov	ar0,r4
   0FA3 8E 82               444 	mov	dpl,r6
   0FA5 8F 83               445 	mov	dph,r7
   0FA7 88 F0               446 	mov	b,r0
   0FA9 12 1B 53            447 	lcall	__gptrget
   0FAC FE                  448 	mov	r6,a
   0FAD 60 29               449 	jz	00113$
                            450 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:165: if(s[n]=='\n')
   0FAF BE 0A 08            451 	cjne	r6,#0x0A,00106$
                            452 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:167: while(!TI);
   0FB2                     453 00101$:
                            454 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:168: TI=0;
   0FB2 10 99 02            455 	jbc	_SCON_1,00126$
   0FB5 80 FB               456 	sjmp	00101$
   0FB7                     457 00126$:
                            458 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:169: SBUF=0x0d;
   0FB7 75 99 0D            459 	mov	_SBUF,#0x0D
                            460 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:171: while(!TI);
   0FBA                     461 00106$:
                            462 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:172: TI=0;
   0FBA 10 99 02            463 	jbc	_SCON_1,00127$
   0FBD 80 FB               464 	sjmp	00106$
   0FBF                     465 00127$:
                            466 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:173: SBUF=s[n];
   0FBF ED                  467 	mov	a,r5
   0FC0 2A                  468 	add	a,r2
   0FC1 FE                  469 	mov	r6,a
   0FC2 E4                  470 	clr	a
   0FC3 3B                  471 	addc	a,r3
   0FC4 FF                  472 	mov	r7,a
   0FC5 8C 00               473 	mov	ar0,r4
   0FC7 8E 82               474 	mov	dpl,r6
   0FC9 8F 83               475 	mov	dph,r7
   0FCB 88 F0               476 	mov	b,r0
   0FCD 12 1B 53            477 	lcall	__gptrget
   0FD0 F5 99               478 	mov	_SBUF,a
                            479 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:174: n++;
   0FD2 0D                  480 	inc	r5
                            481 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:175: if(n>254)
   0FD3 ED                  482 	mov	a,r5
   0FD4 24 01               483 	add	a,#0xff - 0xFE
   0FD6 50 C3               484 	jnc	00111$
                            485 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:176: return;
                            486 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:178: return;
   0FD8                     487 00113$:
   0FD8 22                  488 	ret
                            489 ;------------------------------------------------------------
                            490 ;Allocation info for local variables in function 'rs_send_hex_i'
                            491 ;------------------------------------------------------------
                            492 ;wert                      Allocated to registers 
                            493 ;------------------------------------------------------------
                            494 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:230: void rs_send_hex_i(unsigned int wert)
                            495 ;	-----------------------------------------
                            496 ;	 function rs_send_hex_i
                            497 ;	-----------------------------------------
   0FD9                     498 _rs_send_hex_i:
                            499 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:231: {wert;
   0FD9 22                  500 	ret
                            501 ;------------------------------------------------------------
                            502 ;Allocation info for local variables in function 'rs_send_hex'
                            503 ;------------------------------------------------------------
                            504 ;wert                      Allocated to registers 
                            505 ;------------------------------------------------------------
                            506 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:243: void rs_send_hex(unsigned char wert)
                            507 ;	-----------------------------------------
                            508 ;	 function rs_send_hex
                            509 ;	-----------------------------------------
   0FDA                     510 _rs_send_hex:
                            511 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:245: wert;
   0FDA 22                  512 	ret
                            513 ;------------------------------------------------------------
                            514 ;Allocation info for local variables in function 'rs_send'
                            515 ;------------------------------------------------------------
                            516 ;z                         Allocated to registers r2 
                            517 ;------------------------------------------------------------
                            518 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:254: void rs_send(unsigned char z)
                            519 ;	-----------------------------------------
                            520 ;	 function rs_send
                            521 ;	-----------------------------------------
   0FDB                     522 _rs_send:
   0FDB AA 82               523 	mov	r2,dpl
                            524 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:256: while(!TI);
   0FDD                     525 00101$:
                            526 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:257: TI=0;
   0FDD 10 99 02            527 	jbc	_SCON_1,00108$
   0FE0 80 FB               528 	sjmp	00101$
   0FE2                     529 00108$:
                            530 ;	C:/Freebus/C_Programme/oldisprogramm/com/fb_rs232.c:258: SBUF=z;
   0FE2 8A 99               531 	mov	_SBUF,r2
   0FE4 22                  532 	ret
                            533 	.area CSEG    (CODE)
                            534 	.area CONST   (CODE)
                            535 	.area XINIT   (CODE)
                            536 	.area CABS    (ABS,CODE)
