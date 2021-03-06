# Snapshot report for `test/test.js`

The actual snapshot is saved in `test.js.snap`.

Generated by [AVA](https://ava.li).

## Task basic behavior

> Snapshot 1

    `const answer = 42;␊
    ␊
    const foo = "bar";␊
    ␊
    console.log(foo + answer);␊
    `

## With multiple files

> Snapshot 1

    `const answer = 42;␊
    ␊
    const foo = "bar";␊
    ␊
    console.log(foo + answer);␊
    `

> Snapshot 2

    `console.log("second");␊
    `

## With plugin array

> Snapshot 1

    `␊
    // 1␊
    const answer = 42;␊
    ␊
    const foo = "bar";␊
    ␊
    console.log(foo + answer);␊
    `

> Snapshot 2

    `␊
    // 2␊
    const answer = 42;␊
    ␊
    const foo = "bar";␊
    ␊
    console.log(foo + answer);␊
    `

## With plugin function

> Snapshot 1

    `␊
    // 1␊
    const answer = 42;␊
    ␊
    const foo = "bar";␊
    ␊
    console.log(foo + answer);␊
    `

> Snapshot 2

    `␊
    // 1␊
    const answer = 42;␊
    ␊
    const foo = "bar";␊
    ␊
    console.log(foo + answer);␊
    `

## With source map

> Snapshot 1

    `const answer = 42;␊
    ␊
    const foo = "bar";␊
    ␊
    console.log(foo + answer);␊
    ␊
    //# sourceMappingURL=sourcemap.js.map`

> Snapshot 2

    '{"version":3,"file":"basic.js","sources":["fixtures/module.js","fixtures/basic.js"],"sourcesContent":["const answer = 42;\\n\\nexport default answer;\\n\\nexport const unused = \\"foo\\";\\n","import answer from \\"./module\\";\\n\\nconst foo = \\"bar\\";\\n\\nconsole.log(foo + answer);\\n"],"names":[],"mappings":"AAAA,MAAM,MAAM,GAAG,EAAE,CAAC;;ACElB,MAAM,GAAG,GAAG,KAAK,CAAC;;AAElB,OAAO,CAAC,GAAG,CAAC,GAAG,GAAG,MAAM,CAAC,CAAC"}'

## With source map inline

> Snapshot 1

    `const answer = 42;␊
    ␊
    const foo = "bar";␊
    ␊
    console.log(foo + answer);␊
    ␊
    //# sourceMappingURL=data:application/json;charset=utf-8;base64,eyJ2ZXJzaW9uIjozLCJmaWxlIjoiYmFzaWMuanMiLCJzb3VyY2VzIjpbImZpeHR1cmVzL21vZHVsZS5qcyIsImZpeHR1cmVzL2Jhc2ljLmpzIl0sInNvdXJjZXNDb250ZW50IjpbImNvbnN0IGFuc3dlciA9IDQyO1xuXG5leHBvcnQgZGVmYXVsdCBhbnN3ZXI7XG5cbmV4cG9ydCBjb25zdCB1bnVzZWQgPSBcImZvb1wiO1xuIiwiaW1wb3J0IGFuc3dlciBmcm9tIFwiLi9tb2R1bGVcIjtcblxuY29uc3QgZm9vID0gXCJiYXJcIjtcblxuY29uc29sZS5sb2coZm9vICsgYW5zd2VyKTtcbiJdLCJuYW1lcyI6W10sIm1hcHBpbmdzIjoiQUFBQSxNQUFNLE1BQU0sR0FBRyxFQUFFLENBQUM7O0FDRWxCLE1BQU0sR0FBRyxHQUFHLEtBQUssQ0FBQzs7QUFFbEIsT0FBTyxDQUFDLEdBQUcsQ0FBQyxHQUFHLEdBQUcsTUFBTSxDQUFDLENBQUMifQ==`
