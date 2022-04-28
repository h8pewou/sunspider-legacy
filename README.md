# Sunspider 1.0.2 for legacy devices

## Hosting instructions
1. Git clone this repository.
2. Copy/move files to your webserver's root.
3. Profit.

## Running the tests on legacy devices
Open http://weboslives.eu/sunspider on your web browser and follow on-screen instructions.

## Example results
Here are some results for comparison purposes (I've mixed in more some modern devices as well):

[Palm Pixi Plus webOS 1.4.5.1 (Uberkernel 787 MHz)](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B1254,2581,1352,1330,1514,1463,1515,1470,1367,1342%5D,%223d-morph%22:%5B1912,1850,2616,2223,2131,2197,2182,2207,1923,2089%5D,%223d-raytrace%22:%5B938,918,1028,953,1041,1109,1048,1097,1036,1113%5D,%22access-binary-trees%22:%5B208,275,336,310,290,281,300,245,234,252%5D,%22access-fannkuch%22:%5B716,737,1693,1702,813,809,793,790,766,745%5D,%22access-nbody%22:%5B958,1009,1075,1007,1177,1040,1112,1119,1414,1059%5D,%22access-nsieve%22:%5B453,459,455,456,516,561,486,490,780,465%5D,%22bitops-3bit-bits-in-byte%22:%5B242,199,212,237,208,194,236,247,239,222%5D,%22bitops-bits-in-byte%22:%5B335,390,362,349,394,386,395,391,380,375%5D,%22bitops-bitwise-and%22:%5B531,517,565,579,569,528,536,660,578,610%5D,%22bitops-nsieve-bits%22:%5B832,884,800,759,887,874,814,859,838,782%5D,%22controlflow-recursive%22:%5B96,128,103,118,117,108,111,131,104,118%5D,%22crypto-aes%22:%5B530,518,402,544,517,594,580,437,1236,474%5D,%22crypto-md5%22:%5B304,391,342,359,387,376,390,366,356,342%5D,%22crypto-sha1%22:%5B411,375,337,368,378,364,368,354,328,326%5D,%22date-format-tofte%22:%5B911,959,791,945,972,941,948,889,847,872%5D,%22date-format-xparb%22:%5B1146,1294,1097,1248,1315,1226,1212,1209,1108,1199%5D,%22math-cordic%22:%5B1172,1273,1289,1228,1250,1209,1263,1184,1143,1135%5D,%22math-partial-sums%22:%5B1351,1363,1433,1434,1417,1423,1426,1364,1282,1601%5D,%22math-spectral-norm%22:%5B531,537,544,598,594,545,553,564,533,511%5D,%22regexp-dna%22:%5B264,272,294,296,299,297,294,298,268,267%5D,%22string-base64%22:%5B682,646,626,712,720,715,705,602,615,1349%5D,%22string-fasta%22:%5B1302,1267,1244,1322,1423,1298,1342,1231,1228,1618%5D,%22string-tagcloud%22:%5B850,871,842,934,924,923,943,839,838,815%5D,%22string-unpack-code%22:%5B2218,1591,1609,1758,1739,1742,1759,1568,1638,1565%5D,%22string-validate-input%22:%5B1153,1228,1216,1297,1311,1301,1319,1188,1171,1131%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                 22402.4ms +/- 1.7%
```

[PowerBook G4 on Mac OS X 10.4.11 (1000 MHz)](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B392,394,392,392,392,393,394,393,392,391%5D,%223d-morph%22:%5B528,514,514,514,518,521,517,520,519,519%5D,%223d-raytrace%22:%5B377,374,377,375,374,378,376,373,379,378%5D,%22access-binary-trees%22:%5B129,129,130,130,129,131,131,129,130,131%5D,%22access-fannkuch%22:%5B725,726,724,725,725,723,724,725,726,724%5D,%22access-nbody%22:%5B411,406,406,407,409,410,407,407,407,408%5D,%22access-nsieve%22:%5B275,275,278,276,272,274,275,275,271,276%5D,%22bitops-3bit-bits-in-byte%22:%5B260,261,260,260,259,259,261,260,259,260%5D,%22bitops-bits-in-byte%22:%5B275,276,274,274,275,274,274,274,274,274%5D,%22bitops-bitwise-and%22:%5B253,252,263,252,252,253,252,253,252,253%5D,%22bitops-nsieve-bits%22:%5B460,459,460,460,460,459,462,461,459,460%5D,%22controlflow-recursive%22:%5B153,154,153,155,156,153,153,153,154,154%5D,%22crypto-aes%22:%5B261,258,260,259,259,260,259,259,259,258%5D,%22crypto-md5%22:%5B175,176,176,175,175,176,176,177,175,176%5D,%22crypto-sha1%22:%5B180,177,178,178,178,178,180,178,177,179%5D,%22date-format-tofte%22:%5B250,247,249,248,251,252,250,250,251,249%5D,%22date-format-xparb%22:%5B178,177,176,175,179,181,176,180,182,179%5D,%22math-cordic%22:%5B443,444,443,442,442,443,442,443,442,442%5D,%22math-partial-sums%22:%5B374,379,372,379,373,372,383,378,373,380%5D,%22math-spectral-norm%22:%5B347,348,347,346,345,348,351,349,347,362%5D,%22regexp-dna%22:%5B997,1001,982,1006,983,981,979,983,978,972%5D,%22string-base64%22:%5B232,223,221,218,217,221,220,220,223,222%5D,%22string-fasta%22:%5B338,340,336,334,332,335,338,332,336,338%5D,%22string-tagcloud%22:%5B270,270,270,268,268,268,270,269,268,268%5D,%22string-unpack-code%22:%5B353,351,354,353,355,350,350,353,350,351%5D,%22string-validate-input%22:%5B178,181,182,177,182,182,177,179,179,178%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                  8779.0ms +/- 0.1%
```

[HP Veer on webOS 2.2.4 (stock kernel 800 MHz)](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B342,373,275,241,288,326,230,275,284,267%5D,%223d-morph%22:%5B284,273,363,288,377,270,284,295,369,274%5D,%223d-raytrace%22:%5B227,250,224,225,221,265,256,350,231,348%5D,%22access-binary-trees%22:%5B199,69,37,35,73,69,76,75,55,68%5D,%22access-fannkuch%22:%5B158,179,165,143,164,191,166,163,169,164%5D,%22access-nbody%22:%5B193,183,287,186,298,163,205,206,313,193%5D,%22access-nsieve%22:%5B83,82,77,98,100,85,95,87,81,80%5D,%22bitops-3bit-bits-in-byte%22:%5B58,60,67,65,66,57,63,59,72,60%5D,%22bitops-bits-in-byte%22:%5B99,75,88,95,89,89,92,102,92,92%5D,%22bitops-bitwise-and%22:%5B173,107,112,106,115,106,107,108,110,110%5D,%22bitops-nsieve-bits%22:%5B180,264,278,157,307,262,164,171,254,175%5D,%22controlflow-recursive%22:%5B52,53,50,60,46,55,54,55,68,70%5D,%22crypto-aes%22:%5B142,105,151,144,129,209,119,102,139,104%5D,%22crypto-md5%22:%5B154,142,141,147,144,192,111,149,144,232%5D,%22crypto-sha1%22:%5B129,133,128,212,129,158,108,125,130,146%5D,%22date-format-tofte%22:%5B268,329,222,317,268,446,246,271,336,248%5D,%22date-format-xparb%22:%5B445,465,472,480,436,610,512,407,443,476%5D,%22math-cordic%22:%5B223,221,218,218,212,302,214,222,219,315%5D,%22math-partial-sums%22:%5B259,263,255,344,257,334,281,263,260,259%5D,%22math-spectral-norm%22:%5B124,199,190,123,196,259,110,130,200,122%5D,%22regexp-dna%22:%5B186,190,182,185,184,182,250,184,186,183%5D,%22string-base64%22:%5B109,208,121,224,133,126,123,240,208,230%5D,%22string-fasta%22:%5B235,217,236,244,229,234,239,246,234,238%5D,%22string-tagcloud%22:%5B630,430,428,396,546,580,426,403,443,434%5D,%22string-unpack-code%22:%5B574,566,553,556,572,566,565,563,557,552%5D,%22string-validate-input%22:%5B199,279,255,282,196,213,203,281,227,295%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                  5710.0ms +/- 3.4%
```

[HP Pre 3 on webOS 2.2.4 (Uberkernel 1690 MHz)](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B156,225,175,190,174,171,225,179,154,179%5D,%223d-morph%22:%5B340,164,173,214,209,164,171,161,131,181%5D,%223d-raytrace%22:%5B177,158,231,154,223,208,163,217,168,216%5D,%22access-binary-trees%22:%5B39,24,29,26,20,26,38,26,23,30%5D,%22access-fannkuch%22:%5B105,118,103,100,110,93,100,102,57,103%5D,%22access-nbody%22:%5B156,107,124,191,159,124,149,113,86,120%5D,%22access-nsieve%22:%5B27,27,25,25,32,33,37,31,24,37%5D,%22bitops-3bit-bits-in-byte%22:%5B23,24,23,21,18,24,33,17,32,32%5D,%22bitops-bits-in-byte%22:%5B33,41,41,42,33,52,48,42,63,49%5D,%22bitops-bitwise-and%22:%5B48,50,61,82,44,36,41,55,56,62%5D,%22bitops-nsieve-bits%22:%5B295,192,108,184,103,115,108,108,118,139%5D,%22controlflow-recursive%22:%5B32,17,16,17,21,15,21,23,18,28%5D,%22crypto-aes%22:%5B133,123,96,92,163,97,99,153,205,107%5D,%22crypto-md5%22:%5B100,80,67,80,51,66,88,91,93,140%5D,%22crypto-sha1%22:%5B102,85,83,90,58,72,72,64,80,83%5D,%22date-format-tofte%22:%5B141,212,166,154,145,159,155,157,190,163%5D,%22date-format-xparb%22:%5B238,233,256,232,278,253,256,287,319,244%5D,%22math-cordic%22:%5B138,143,196,141,192,192,189,139,139,188%5D,%22math-partial-sums%22:%5B146,157,152,159,151,156,149,158,150,153%5D,%22math-spectral-norm%22:%5B54,233,64,74,55,65,70,57,65,75%5D,%22regexp-dna%22:%5B89,89,90,91,90,92,90,90,90,95%5D,%22string-base64%22:%5B66,60,76,73,65,64,75,57,74,81%5D,%22string-fasta%22:%5B134,144,144,139,137,153,137,113,153,150%5D,%22string-tagcloud%22:%5B226,212,212,203,227,272,210,211,221,221%5D,%22string-unpack-code%22:%5B306,281,277,322,356,291,275,273,300,278%5D,%22string-validate-input%22:%5B130,127,170,118,130,156,139,103,142,178%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                 3217.3ms +/- 2.6%
```

[iPhone 4 on iOS 6.1.3 (800 MHz)](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B159,159,161,158,155,158,159,158,157,158%5D,%223d-morph%22:%5B128,129,131,149,129,130,132,130,130,131%5D,%223d-raytrace%22:%5B209,200,199,200,197,198,198,198,198,204%5D,%22access-binary-trees%22:%5B46,42,43,43,43,43,44,44,43,43%5D,%22access-fannkuch%22:%5B87,82,83,83,83,83,83,84,82,83%5D,%22access-nbody%22:%5B78,77,78,74,87,76,75,78,75,75%5D,%22access-nsieve%22:%5B55,53,51,51,52,53,51,54,52,55%5D,%22bitops-3bit-bits-in-byte%22:%5B10,9,9,11,10,10,11,11,9,11%5D,%22bitops-bits-in-byte%22:%5B26,26,26,26,25,26,26,26,27,26%5D,%22bitops-bitwise-and%22:%5B54,55,53,53,56,54,54,55,55,57%5D,%22bitops-nsieve-bits%22:%5B37,38,37,37,39,58,37,38,37,37%5D,%22controlflow-recursive%22:%5B29,31,28,29,29,31,29,31,29,31%5D,%22crypto-aes%22:%5B141,159,146,138,148,142,139,142,140,144%5D,%22crypto-md5%22:%5B53,53,51,51,55,53,54,56,54,55%5D,%22crypto-sha1%22:%5B40,37,38,40,80,39,39,39,37,40%5D,%22date-format-tofte%22:%5B228,236,227,226,249,237,247,226,227,227%5D,%22date-format-xparb%22:%5B255,258,244,251,252,270,251,261,249,253%5D,%22math-cordic%22:%5B93,91,91,96,90,90,90,90,89,89%5D,%22math-partial-sums%22:%5B154,152,155,153,148,149,155,154,148,146%5D,%22math-spectral-norm%22:%5B57,57,59,57,58,59,70,58,58,56%5D,%22regexp-dna%22:%5B119,113,118,126,115,111,114,111,112,115%5D,%22string-base64%22:%5B81,80,83,76,82,82,81,84,82,83%5D,%22string-fasta%22:%5B130,132,130,131,133,130,135,134,129,139%5D,%22string-tagcloud%22:%5B205,175,172,173,187,189,209,193,182,190%5D,%22string-unpack-code%22:%5B361,388,368,372,361,356,380,369,423,359%5D,%22string-validate-input%22:%5B136,142,126,123,132,130,137,132,130,132%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                 2958.0ms +/- 0.7%
```

[Samsung AU8002 Smart TV on Tizen 6.0](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B60,58,58,58,58,58,57,58,59,63%5D,%223d-morph%22:%5B47,47,45,46,46,46,46,46,45,46%5D,%223d-raytrace%22:%5B79,77,85,77,77,94,76,77,76,76%5D,%22access-binary-trees%22:%5B19,17,18,17,17,18,18,17,17,17%5D,%22access-fannkuch%22:%5B62,62,62,62,62,63,63,62,62,62%5D,%22access-nbody%22:%5B26,25,32,25,30,29,27,27,25,26%5D,%22access-nsieve%22:%5B37,38,38,38,38,38,38,38,37,40%5D,%22bitops-3bit-bits-in-byte%22:%5B10,11,10,11,11,11,11,11,11,11%5D,%22bitops-bits-in-byte%22:%5B21,21,21,20,21,20,21,21,17,21%5D,%22bitops-bitwise-and%22:%5B13,13,13,13,13,13,13,13,13,13%5D,%22bitops-nsieve-bits%22:%5B29,28,28,28,29,28,28,29,29,29%5D,%22controlflow-recursive%22:%5B16,16,16,16,17,16,15,16,16,15%5D,%22crypto-aes%22:%5B57,48,60,55,62,55,47,55,55,57%5D,%22crypto-md5%22:%5B45,46,45,47,46,44,46,45,44,47%5D,%22crypto-sha1%22:%5B58,58,59,57,55,57,55,57,57,58%5D,%22date-format-tofte%22:%5B66,66,66,61,61,63,60,63,65,65%5D,%22date-format-xparb%22:%5B58,57,60,60,58,57,61,58,60,59%5D,%22math-cordic%22:%5B24,32,32,32,31,32,32,24,31,24%5D,%22math-partial-sums%22:%5B90,90,91,92,91,89,91,92,89,91%5D,%22math-spectral-norm%22:%5B17,17,17,17,16,16,17,16,17,17%5D,%22regexp-dna%22:%5B25,25,25,25,25,25,25,26,25,25%5D,%22string-base64%22:%5B69,67,67,68,68,66,68,67,68,68%5D,%22string-fasta%22:%5B61,61,61,61,61,61,61,61,61,61%5D,%22string-tagcloud%22:%5B107,108,87,86,96,96,96,97,96,96%5D,%22string-unpack-code%22:%5B72,73,72,71,73,72,72,72,72,72%5D,%22string-validate-input%22:%5B64,50,48,52,55,47,49,49,53,52%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                 1208.6ms +/- 0.7%
```

[Dell Latitude 7400 i5-8365U on Windows 10 (4100 MHz)](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B10,9,10,11,10,10,9,10,12,11%5D,%223d-morph%22:%5B9,8,9,9,9,10,9,9,9,10%5D,%223d-raytrace%22:%5B10,9,10,11,12,9,10,11,9,16%5D,%22access-binary-trees%22:%5B3,2,2,2,3,2,3,3,2,4%5D,%22access-fannkuch%22:%5B13,12,14,12,14,12,13,12,12,17%5D,%22access-nbody%22:%5B9,5,5,4,5,4,5,5,5,6%5D,%22access-nsieve%22:%5B6,6,6,6,6,6,6,7,6,9%5D,%22bitops-3bit-bits-in-byte%22:%5B2,2,2,2,2,2,3,2,2,3%5D,%22bitops-bits-in-byte%22:%5B4,3,5,4,4,4,4,4,4,6%5D,%22bitops-bitwise-and%22:%5B3,3,3,3,3,3,3,3,3,3%5D,%22bitops-nsieve-bits%22:%5B5,5,5,6,6,5,6,7,6,7%5D,%22controlflow-recursive%22:%5B3,5,4,4,3,3,3,4,3,4%5D,%22crypto-aes%22:%5B6,8,8,5,6,7,6,7,5,8%5D,%22crypto-md5%22:%5B6,6,6,6,7,5,6,6,7,9%5D,%22crypto-sha1%22:%5B10,11,9,9,10,10,10,10,10,14%5D,%22date-format-tofte%22:%5B8,8,7,7,7,7,7,7,9,9%5D,%22date-format-xparb%22:%5B7,9,7,12,8,7,7,8,7,9%5D,%22math-cordic%22:%5B5,5,6,5,5,5,13,5,6,7%5D,%22math-partial-sums%22:%5B14,15,16,14,14,14,15,14,16,17%5D,%22math-spectral-norm%22:%5B2,2,3,3,2,2,2,4,2,2%5D,%22regexp-dna%22:%5B5,5,5,5,5,6,6,5,5,6%5D,%22string-base64%22:%5B9,9,9,11,9,10,11,12,10,11%5D,%22string-fasta%22:%5B10,9,15,10,9,9,9,10,10,12%5D,%22string-tagcloud%22:%5B12,12,26,13,11,12,12,11,11,19%5D,%22string-unpack-code%22:%5B9,12,13,10,9,9,12,9,10,11%5D,%22string-validate-input%22:%5B8,11,10,8,8,11,10,8,12,9%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                 198.2ms +/- 6.0%
```

[iPhone 8](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B9,7,9,9,9,9,8,9,8,9%5D,%223d-morph%22:%5B6,5,6,6,6,6,6,6,6,6%5D,%223d-raytrace%22:%5B5,5,6,5,5,5,5,5,5,5%5D,%22access-binary-trees%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22access-fannkuch%22:%5B6,6,6,6,6,6,6,6,6,6%5D,%22access-nbody%22:%5B4,3,4,4,4,3,4,3,4,4%5D,%22access-nsieve%22:%5B3,3,3,3,3,3,3,3,3,3%5D,%22bitops-3bit-bits-in-byte%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22bitops-bits-in-byte%22:%5B3,3,3,3,3,3,3,3,3,3%5D,%22bitops-bitwise-and%22:%5B3,3,3,3,3,3,3,3,3,3%5D,%22bitops-nsieve-bits%22:%5B5,5,5,6,5,5,5,5,5,5%5D,%22controlflow-recursive%22:%5B2,2,2,2,2,2,4,2,2,2%5D,%22crypto-aes%22:%5B5,5,5,5,5,5,5,12,5,5%5D,%22crypto-md5%22:%5B2,2,3,3,2,2,3,2,2,2%5D,%22crypto-sha1%22:%5B3,3,3,3,3,3,4,3,3,3%5D,%22date-format-tofte%22:%5B8,8,8,8,8,8,8,8,8,8%5D,%22date-format-xparb%22:%5B6,6,6,6,6,6,6,8,6,6%5D,%22math-cordic%22:%5B4,4,4,4,4,4,4,4,4,4%5D,%22math-partial-sums%22:%5B4,4,4,5,4,4,4,4,4,4%5D,%22math-spectral-norm%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22regexp-dna%22:%5B10,10,10,10,10,10,10,9,10,9%5D,%22string-base64%22:%5B4,4,4,4,4,4,4,4,4,4%5D,%22string-fasta%22:%5B6,6,6,6,6,6,6,6,6,6%5D,%22string-tagcloud%22:%5B11,10,9,10,10,11,11,10,10,10%5D,%22string-unpack-code%22:%5B22,24,24,23,23,23,29,23,23,23%5D,%22string-validate-input%22:%5B5,5,5,5,5,5,7,5,5,5%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                 142.9ms +/- 2.2%
```

[iPhone XR](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B8,7,9,9,9,7,9,5,8,10%5D,%223d-morph%22:%5B6,6,6,5,6,6,6,4,6,6%5D,%223d-raytrace%22:%5B4,4,4,4,5,5,5,4,6,5%5D,%22access-binary-trees%22:%5B2,1,1,1,1,1,1,3,1,1%5D,%22access-fannkuch%22:%5B5,5,5,5,4,4,5,5,5,5%5D,%22access-nbody%22:%5B3,3,3,3,3,2,3,2,2,2%5D,%22access-nsieve%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22bitops-3bit-bits-in-byte%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22bitops-bits-in-byte%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22bitops-bitwise-and%22:%5B2,3,2,2,2,2,2,2,2,2%5D,%22bitops-nsieve-bits%22:%5B4,4,4,4,4,4,4,4,4,4%5D,%22controlflow-recursive%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22crypto-aes%22:%5B4,4,4,4,4,4,4,4,4,4%5D,%22crypto-md5%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22crypto-sha1%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22date-format-tofte%22:%5B6,6,6,6,6,6,6,6,6,6%5D,%22date-format-xparb%22:%5B4,4,4,5,5,4,5,5,5,5%5D,%22math-cordic%22:%5B3,3,3,3,3,3,3,3,3,3%5D,%22math-partial-sums%22:%5B4,4,4,4,4,3,4,4,4,4%5D,%22math-spectral-norm%22:%5B1,2,1,1,2,1,2,2,2,2%5D,%22regexp-dna%22:%5B7,7,7,7,7,7,7,7,7,7%5D,%22string-base64%22:%5B3,3,3,3,3,4,3,3,3,4%5D,%22string-fasta%22:%5B5,5,5,5,5,5,5,5,5,5%5D,%22string-tagcloud%22:%5B8,8,7,7,7,7,7,7,7,7%5D,%22string-unpack-code%22:%5B18,18,18,19,18,18,18,18,19,19%5D,%22string-validate-input%22:%5B6,4,6,4,6,4,4,4,4,4%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                 112.6ms +/- 1.7%
```

[iPhone 12](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B5,6,6,6,6,6,6,6,6,6%5D,%223d-morph%22:%5B3,4,4,4,4,4,4,4,4,4%5D,%223d-raytrace%22:%5B4,3,3,3,3,3,3,3,3,3%5D,%22access-binary-trees%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22access-fannkuch%22:%5B3,3,3,3,3,3,3,3,3,3%5D,%22access-nbody%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22access-nsieve%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22bitops-3bit-bits-in-byte%22:%5B0,0,0,0,0,0,0,0,0,0%5D,%22bitops-bits-in-byte%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22bitops-bitwise-and%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22bitops-nsieve-bits%22:%5B3,3,3,3,3,3,3,3,3,3%5D,%22controlflow-recursive%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22crypto-aes%22:%5B2,2,3,4,2,2,2,3,2,2%5D,%22crypto-md5%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22crypto-sha1%22:%5B1,1,2,1,1,1,1,1,1,2%5D,%22date-format-tofte%22:%5B4,4,4,4,4,4,4,4,4,4%5D,%22date-format-xparb%22:%5B3,3,3,3,3,3,3,3,3,6%5D,%22math-cordic%22:%5B2,2,2,2,2,1,2,1,2,2%5D,%22math-partial-sums%22:%5B2,3,2,2,2,2,2,3,2,2%5D,%22math-spectral-norm%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22regexp-dna%22:%5B5,5,5,5,5,5,5,5,5,5%5D,%22string-base64%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22string-fasta%22:%5B3,3,3,3,3,3,3,3,3,4%5D,%22string-tagcloud%22:%5B5,5,5,5,5,5,6,5,5,7%5D,%22string-unpack-code%22:%5B14,14,16,16,15,15,15,15,15,15%5D,%22string-validate-input%22:%5B3,2,2,2,3,2,2,2,2,2%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                  76.4ms +/- 2.3%
```

[MacBook Air M1 2020 (3200 MHz)](http://weboslives.eu/sunspider/sunspider-1.0.2/results.html?%7B%22v%22:%20%22sunspider-1.0.2%22,%20%223d-cube%22:%5B6,5,5,6,6,6,4,6,5,5%5D,%223d-morph%22:%5B4,4,4,4,4,4,4,4,4,4%5D,%223d-raytrace%22:%5B3,3,3,3,3,3,3,3,3,3%5D,%22access-binary-trees%22:%5B1,1,1,1,1,2,1,1,1,1%5D,%22access-fannkuch%22:%5B4,4,4,4,4,4,4,4,4,4%5D,%22access-nbody%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22access-nsieve%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22bitops-3bit-bits-in-byte%22:%5B0,0,0,0,0,0,0,0,0,0%5D,%22bitops-bits-in-byte%22:%5B1,1,1,2,1,2,1,1,1,1%5D,%22bitops-bitwise-and%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22bitops-nsieve-bits%22:%5B3,3,3,3,3,3,3,3,3,3%5D,%22controlflow-recursive%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22crypto-aes%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22crypto-md5%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22crypto-sha1%22:%5B1,1,2,2,1,1,1,1,1,1%5D,%22date-format-tofte%22:%5B4,5,3,4,4,3,3,5,4,4%5D,%22date-format-xparb%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22math-cordic%22:%5B1,1,1,2,1,1,2,1,1,3%5D,%22math-partial-sums%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22math-spectral-norm%22:%5B1,1,1,1,1,1,1,1,1,1%5D,%22regexp-dna%22:%5B6,5,6,6,5,5,5,5,6,5%5D,%22string-base64%22:%5B2,2,2,2,2,2,2,2,2,2%5D,%22string-fasta%22:%5B3,3,3,3,3,3,3,3,3,3%5D,%22string-tagcloud%22:%5B5,5,5,5,5,5,4,4,5,4%5D,%22string-unpack-code%22:%5B12,12,13,13,13,13,13,13,13,13%5D,%22string-validate-input%22:%5B2,2,2,2,2,2,2,2,2,2%5D%7D)

```
RESULTS (means and 95% confidence intervals)
--------------------------------------------
Total:                  71.1ms +/- 1.7%
```
