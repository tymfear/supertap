# Snapshot report for `test/test.js`

The actual snapshot is saved in `test.js.snap`.

Generated by [AVA](https://ava.li).

## faucet - fail

> Snapshot 1

    `␍
    # fail[K␊
    ␍
      not ok [1m[31m1[0m fail[K␊
    [2A[1G[1m[31m⨯ fail[0m[2B[1G    ---␊
          actual: 1␊
          expected: 2␊
          operator: ===␊
          name: Error␊
          message: error␊
          at: 'fn (test.js:1:2)'␊
        ...␊
      ␊
    ␍
    # tests 1[K␊
    ␍
    tests 1␍
    # pass 0[K␊
    ␍
    pass 0␍
    # fail 1[K␊
    [1A[1G[1m[31m⨯ fail 1[0m[1B[1G`

## faucet - fail-without-error

> Snapshot 1

    `␍
    # fail[K␊
    ␍
      not ok [1m[31m1[0m fail[K␊
    [2A[1G[1m[31m⨯ fail[0m[2B[1G  ␊
    ␍
    # tests 1[K␊
    ␍
    tests 1␍
    # pass 0[K␊
    ␍
    pass 0␍
    # fail 1[K␊
    [1A[1G[1m[31m⨯ fail 1[0m[1B[1G`

## faucet - mixed

> Snapshot 1

    `␍
    # passing[K␊
    ␍
      ok [1m[32m1[0m passing[K␍
    [1A[1G[1m[32m✓ passing[0m[1B[1G␍
    # fail[K␊
    ␍
      not ok [1m[31m2[0m fail[K␊
    [2A[1G[1m[31m⨯ fail[0m[2B[1G    ---␊
          actual: 1␊
          expected: 2␊
          operator: ===␊
          name: Error␊
          message: error␊
          at: 'fn (test.js:1:2)'␊
        ...␊
    ␍
    # pass with comment[K␊
    ␍
      ok [1m[32m3[0m pass with comment[K␍
    [1A[1G[1m[32m✓ pass with comment[0m[1B[1G␍
    # pass with comment[K␊
    ␍
      ok [1m[32m4[0m pass with comment[K␍
    [1A[1G[1m[32m✓ pass with comment[0m[1B[1G␍
    # skip[K␊
    ␍
      ok [1m[32m5[0m skip # SKIP[K␍
    [1A[1G[1m[32m✓ skip[0m[1B[1G␍
    # todo[K␊
    ␍
      not ok [1m[31m6[0m todo # TODO[K␊
    [2A[1G[1m[31m⨯ todo[0m[2B[1G  ␊
    ␍
    # tests 5[K␊
    ␍
    tests 5␍
    # pass 3[K␊
    ␍
    pass 3␍
    # skip 1[K␊
    ␍
    [1A[1G[1m[32m✓ skip 1[0m[1B[1G␍
    # fail 2[K␊
    [1A[1G[1m[31m⨯ fail 2[0m[1B[1G`

## faucet - pass

> Snapshot 1

    `␍
    # passing[K␊
    ␍
      ok [1m[32m1[0m passing[K␍
    [1A[1G[1m[32m✓ passing[0m[1B[1G␍
    # tests 1[K␊
    ␍
    tests 1␍
    # pass 1[K␊
    [1A[1G[1m[32m✓ pass 1[0m[1B[1G`

## faucet - pass-fail

> Snapshot 1

    `␍
    # passing[K␊
    ␍
      ok [1m[32m1[0m passing[K␍
    [1A[1G[1m[32m✓ passing[0m[1B[1G␍
    # fail[K␊
    ␍
      not ok [1m[31m2[0m fail[K␊
    [2A[1G[1m[31m⨯ fail[0m[2B[1G    ---␊
          actual: 1␊
          expected: 2␊
          operator: ===␊
          name: Error␊
          message: error␊
          at: 'fn (test.js:1:2)'␊
        ...␊
      ␊
    ␍
    # tests 2[K␊
    ␍
    tests 2␍
    # pass 1[K␊
    ␍
    pass 1␍
    # fail 1[K␊
    [1A[1G[1m[31m⨯ fail 1[0m[1B[1G`

## faucet - pass-with-multiple-comments

> Snapshot 1

    `␍
    # pass with comment[K␊
    ␍
      ok [1m[32m1[0m pass with comment[K␍
    [1A[1G[1m[32m✓ pass with comment[0m[1B[1G␍
    # tests 1[K␊
    ␍
    tests 1␍
    # pass 1[K␊
    [1A[1G[1m[32m✓ pass 1[0m[1B[1G`

## faucet - pass-with-single-comment

> Snapshot 1

    `␍
    # pass with comment[K␊
    ␍
      ok [1m[32m1[0m pass with comment[K␍
    [1A[1G[1m[32m✓ pass with comment[0m[1B[1G␍
    # tests 1[K␊
    ␍
    tests 1␍
    # pass 1[K␊
    [1A[1G[1m[32m✓ pass 1[0m[1B[1G`

## faucet - skip

> Snapshot 1

    `␍
    # skip[K␊
    ␍
      ok [1m[32m1[0m skip # SKIP[K␍
    [1A[1G[1m[32m✓ skip[0m[1B[1G␍
    # tests 1[K␊
    ␍
    tests 1␍
    # pass 0[K␊
    ␍
    pass 0␍
    # skip 1[K␊
    [1A[1G[1m[32m✓ skip 1[0m[1B[1G`

## faucet - todo

> Snapshot 1

    `␍
    # todo[K␊
    ␍
      not ok [1m[31m1[0m todo # TODO[K␊
    [2A[1G[1m[31m⨯ todo[0m[2B[1G  ␊
    ␍
    # tests 0[K␊
    ␍
    tests 0␍
    # pass 0[K␊
    ␍
    pass 0␍
    # fail 1[K␊
    [1A[1G[1m[31m⨯ fail 1[0m[1B[1G`

## tap-dot - fail

> Snapshot 1

    `␊
    x  ␊
    ␊
    ␊
      ---␊
        actual: 1␊
        expected: 2␊
        operator: ===␊
        name: Error␊
        message: error␊
        at: 'fn (test.js:1:2)'␊
      ...␊
    ␊
      ␊
    ␊
      1 tests␊
      0 passed␊
      1 failed  ␊
    ␊
      Failed Tests:   There was 1 failure␊
    ␊
        x fail␊
      ␊
    `

## tap-dot - fail-without-error

> Snapshot 1

    `␊
    x  ␊
    ␊
    ␊
      ---␊
    undefined␊
      ...␊
    ␊
      ␊
    ␊
      1 tests␊
      0 passed␊
      1 failed  ␊
    ␊
      Failed Tests:   There was 1 failure␊
    ␊
        x fail␊
      ␊
    `

## tap-dot - mixed

> Snapshot 1

    `␊
      .x...x  ␊
    ␊
    ␊
      ---␊
        actual: 1␊
        expected: 2␊
        operator: ===␊
        name: Error␊
        message: error␊
        at: 'fn (test.js:1:2)'␊
      ...␊
      ---␊
    undefined␊
      ...␊
    ␊
      ␊
    ␊
      6 tests␊
      4 passed␊
      2 failed  ␊
    ␊
      Failed Tests:   There were 2 failures␊
    ␊
        x fail␊
        x todo # TODO␊
      ␊
    `

## tap-dot - pass

> Snapshot 1

    `␊
      .  ␊
    ␊
      1 tests␊
      1 passed␊
      ␊
      Pass!`

## tap-dot - pass-fail

> Snapshot 1

    `␊
      .x  ␊
    ␊
    ␊
      ---␊
        actual: 1␊
        expected: 2␊
        operator: ===␊
        name: Error␊
        message: error␊
        at: 'fn (test.js:1:2)'␊
      ...␊
    ␊
      ␊
    ␊
      2 tests␊
      1 passed␊
      1 failed  ␊
    ␊
      Failed Tests:   There was 1 failure␊
    ␊
        x fail␊
      ␊
    `

## tap-dot - pass-with-multiple-comments

> Snapshot 1

    `␊
      .  ␊
    ␊
      1 tests␊
      1 passed␊
      ␊
      Pass!`

## tap-dot - pass-with-single-comment

> Snapshot 1

    `␊
      .  ␊
    ␊
      1 tests␊
      1 passed␊
      ␊
      Pass!`

## tap-dot - skip

> Snapshot 1

    `␊
      .  ␊
    ␊
      1 tests␊
      1 passed␊
      ␊
      Pass!`

## tap-dot - todo

> Snapshot 1

    `␊
    x  ␊
    ␊
    ␊
      ---␊
    undefined␊
      ...␊
    ␊
      ␊
    ␊
      1 tests␊
      0 passed␊
      1 failed  ␊
    ␊
      Failed Tests:   There was 1 failure␊
    ␊
        x todo # TODO␊
      ␊
    `

## tap-json - fail

> Snapshot 1

    '{"stats":{"asserts":1,"passes":0,"failures":1},"asserts":[{"number":1,"comment":"fail","name":"fail","ok":false,"extra":{"actual":"1","expected":"2","operator":"==="}}]}'

## tap-json - fail-without-error

> Snapshot 1

    '{"stats":{"asserts":1,"passes":0,"failures":1},"asserts":[{"number":1,"comment":"fail","name":"fail","ok":false,"extra":{}}]}'

## tap-json - mixed

> Snapshot 1

    '{"stats":{"asserts":6,"passes":4,"failures":2},"asserts":[{"number":1,"comment":"passing","name":"passing","ok":true,"extra":{}},{"number":2,"comment":"fail","name":"fail","ok":false,"extra":{"actual":"1","expected":"2","operator":"==="}},{"number":3,"comment":"pass with comment","name":"pass with comment","ok":true,"extra":{}},{"number":4,"comment":"pass with comment","name":"pass with comment","ok":true,"extra":{}},{"number":5,"comment":"skip","name":"skip # SKIP","ok":true,"extra":{}},{"number":6,"comment":"todo","name":"todo # TODO","ok":false,"extra":{}}]}'

## tap-json - pass

> Snapshot 1

    '{"stats":{"asserts":1,"passes":1,"failures":0},"asserts":[{"number":1,"comment":"passing","name":"passing","ok":true,"extra":{}}]}'

## tap-json - pass-fail

> Snapshot 1

    '{"stats":{"asserts":2,"passes":1,"failures":1},"asserts":[{"number":1,"comment":"passing","name":"passing","ok":true,"extra":{}},{"number":2,"comment":"fail","name":"fail","ok":false,"extra":{"actual":"1","expected":"2","operator":"==="}}]}'

## tap-json - pass-with-multiple-comments

> Snapshot 1

    '{"stats":{"asserts":1,"passes":1,"failures":0},"asserts":[{"number":1,"comment":"pass with comment","name":"pass with comment","ok":true,"extra":{}}]}'

## tap-json - pass-with-single-comment

> Snapshot 1

    '{"stats":{"asserts":1,"passes":1,"failures":0},"asserts":[{"number":1,"comment":"pass with comment","name":"pass with comment","ok":true,"extra":{}}]}'

## tap-json - skip

> Snapshot 1

    '{"stats":{"asserts":1,"passes":1,"failures":0},"asserts":[{"number":1,"comment":"skip","name":"skip # SKIP","ok":true,"extra":{}}]}'

## tap-json - todo

> Snapshot 1

    '{"stats":{"asserts":1,"passes":0,"failures":1},"asserts":[{"number":1,"comment":"todo","name":"todo # TODO","ok":false,"extra":{}}]}'

## tap-min - fail

> Snapshot 1

    `␊
    fail␊
    	operator: ===␊
    	expected: 2␊
    	actual:   1␊
    ␊
    1 test complete ()␊
    `

## tap-min - fail-without-error

> Snapshot 1

    `␊
    fail␊
    ␊
    1 test complete ()␊
    `

## tap-min - mixed

> Snapshot 1

    `␊
    fail␊
    	operator: ===␊
    	expected: 2␊
    	actual:   1␊
    ␊
    todo␊
    ␊
    6 tests complete ()␊
    `

## tap-min - pass

> Snapshot 1

    `␊
    1 test complete ()`

## tap-min - pass-fail

> Snapshot 1

    `␊
    fail␊
    	operator: ===␊
    	expected: 2␊
    	actual:   1␊
    ␊
    2 tests complete ()␊
    `

## tap-min - pass-with-multiple-comments

> Snapshot 1

    `␊
    1 test complete ()`

## tap-min - pass-with-single-comment

> Snapshot 1

    `␊
    1 test complete ()`

## tap-min - skip

> Snapshot 1

    `␊
    1 test complete ()`

## tap-min - todo

> Snapshot 1

    `␊
    todo␊
    ␊
    1 test complete ()`

## tap-nyan - fail

> Snapshot 1

    ` [32m0[0m␊
     [31m1[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [4A[6C_,------,␊
    [6C_|   /\\_/\\ ␊
    [6C^|__( x .x) ␊
    [6C  ""  "" ␊
    [4A␊
    ␊
    ␊
    ␊
      Failed Tests: There was 1 failure␊
    ␊
        ✗ # fail␊
    : fail`

## tap-nyan - fail-without-error

> Snapshot 1

    ` [32m0[0m␊
     [31m1[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [4A[6C_,------,␊
    [6C_|   /\\_/\\ ␊
    [6C^|__( x .x) ␊
    [6C  ""  "" ␊
    [4A␊
    ␊
    ␊
    ␊
      Failed Tests: There was 1 failure␊
    ␊
        ✗ # fail␊
    : fail`

## tap-nyan - mixed

> Snapshot 1

    ` [32m1[0m␊
     [31m0[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [4A[6C_,------,␊
    [6C_|   /\\_/\\ ␊
    [6C^|__( ^ .^) ␊
    [6C  ""  "" ␊
    [4A [32m1[0m␊
     [31m1[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m[38;5;154m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m␊
    [4A[7C_,------,␊
    [7C_|  /\\_/\\ ␊
    [7C~|_( x .x) ␊
    [7C ""  "" ␊
    [4A [32m2[0m␊
     [31m1[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m␊
    [4A[8C_,------,␊
    [8C_|   /\\_/\\ ␊
    [8C^|__( x .x) ␊
    [8C  ""  "" ␊
    [4A [32m3[0m␊
     [31m1[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m␊
    [4A[9C_,------,␊
    [9C_|  /\\_/\\ ␊
    [9C~|_( x .x) ␊
    [9C ""  "" ␊
    [4A [32m4[0m␊
     [31m1[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m[38;5;184m-[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m[38;5;184m-[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m[38;5;184m-[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m[38;5;184m-[0m␊
    [4A[10C_,------,␊
    [10C_|   /\\_/\\ ␊
    [10C^|__( x .x) ␊
    [10C  ""  "" ␊
    [4A [32m4[0m␊
     [31m2[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m[38;5;184m-[0m[38;5;214m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m[38;5;184m-[0m[38;5;214m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m[38;5;184m-[0m[38;5;214m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m[38;5;154m-[0m[38;5;184m_[0m[38;5;184m-[0m[38;5;214m_[0m␊
    [4A[11C_,------,␊
    [11C_|  /\\_/\\ ␊
    [11C~|_( x .x) ␊
    [11C ""  "" ␊
    [4A␊
    ␊
    ␊
    ␊
      Failed Tests: There were 2 failures␊
    ␊
        ✗ # fail␊
    : fail␊
        ✗ # todo␊
    : todo`

## tap-nyan - pass

> Snapshot 1

    ` [32m1[0m␊
     [31m0[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [4A[6C_,------,␊
    [6C_|   /\\_/\\ ␊
    [6C^|__( ^ .^) ␊
    [6C  ""  "" ␊
    [4A␊
    ␊
    ␊
    ␊
      Pass!`

## tap-nyan - pass-fail

> Snapshot 1

    ` [32m1[0m␊
     [31m0[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [4A[6C_,------,␊
    [6C_|   /\\_/\\ ␊
    [6C^|__( ^ .^) ␊
    [6C  ""  "" ␊
    [4A [32m1[0m␊
     [31m1[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m[38;5;154m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m␊
    [5C[38;5;154m-[0m[38;5;154m_[0m␊
    [4A[7C_,------,␊
    [7C_|  /\\_/\\ ␊
    [7C~|_( x .x) ␊
    [7C ""  "" ␊
    [4A␊
    ␊
    ␊
    ␊
      Failed Tests: There was 1 failure␊
    ␊
        ✗ # fail␊
    : fail`

## tap-nyan - pass-with-multiple-comments

> Snapshot 1

    ` [32m1[0m␊
     [31m0[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [4A[6C_,------,␊
    [6C_|   /\\_/\\ ␊
    [6C^|__( ^ .^) ␊
    [6C  ""  "" ␊
    [4A␊
    ␊
    ␊
    ␊
      Pass!`

## tap-nyan - pass-with-single-comment

> Snapshot 1

    ` [32m1[0m␊
     [31m0[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [4A[6C_,------,␊
    [6C_|   /\\_/\\ ␊
    [6C^|__( ^ .^) ␊
    [6C  ""  "" ␊
    [4A␊
    ␊
    ␊
    ␊
      Pass!`

## tap-nyan - skip

> Snapshot 1

    ` [32m1[0m␊
     [31m0[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [4A[6C_,------,␊
    [6C_|   /\\_/\\ ␊
    [6C^|__( ^ .^) ␊
    [6C  ""  "" ␊
    [4A␊
    ␊
    ␊
    ␊
      Pass!`

## tap-nyan - todo

> Snapshot 1

    ` [32m0[0m␊
     [31m1[0m␊
     [36m0[0m␊
    ␊
    [4A[5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [5C[38;5;154m-[0m␊
    [4A[6C_,------,␊
    [6C_|   /\\_/\\ ␊
    [6C^|__( x .x) ␊
    [6C  ""  "" ␊
    [4A␊
    ␊
    ␊
    ␊
      Failed Tests: There was 1 failure␊
    ␊
        ✗ # todo␊
    : todo`

## tap-pessimist - fail

> Snapshot 1

    ''

## tap-pessimist - fail-without-error

> Snapshot 1

    ''

## tap-pessimist - mixed

> Snapshot 1

    ''

## tap-pessimist - pass

> Snapshot 1

    ''

## tap-pessimist - pass-fail

> Snapshot 1

    ''

## tap-pessimist - pass-with-multiple-comments

> Snapshot 1

    ''

## tap-pessimist - pass-with-single-comment

> Snapshot 1

    ''

## tap-pessimist - skip

> Snapshot 1

    ''

## tap-pessimist - todo

> Snapshot 1

    ''

## tap-spec - fail

> Snapshot 1

    `␊
      fail␊
    ␊
    ␊
        ✖ fail␊
        -------␊
          actual: 1␊
          expected: 2␊
          operator: ===␊
          name: Error␊
          message: error␊
          at: 'fn (test.js:1:2)'␊
    ␊
    ␊
    ␊
    ␊
      Failed Tests: There was 1 failure␊
    ␊
        fail␊
    ␊
          ✖ fail␊
    ␊
    ␊
      total:     1␊
      passing:   0␊
      failing:   1␊
      duration:  ␊
    ␊
    ␊
    `

## tap-spec - fail-without-error

> Snapshot 1

    `␊
      fail␊
    ␊
    ␊
    ␊
    ␊
      Failed Tests: There was 1 failure␊
    ␊
        fail␊
    ␊
          ✖ fail␊
    ␊
    ␊
      total:     1␊
      passing:   0␊
      failing:   1␊
      duration:  ␊
    ␊
    `

## tap-spec - mixed

> Snapshot 1

    `␊
      passing␊
    ␊
        ✔ passing␊
    ␊
      fail␊
    ␊
    ␊
        ✖ fail␊
        -------␊
          actual: 1␊
          expected: 2␊
          operator: ===␊
          name: Error␊
          message: error␊
          at: 'fn (test.js:1:2)'␊
    ␊
    ␊
      pass with comment␊
    ␊
        ✔ pass with comment␊
          * Hello␊
    ␊
      pass with comment␊
    ␊
        ✔ pass with comment␊
          * Hello␊
          * Bonjour␊
    ␊
      skip␊
    ␊
        ✔ skip # SKIP␊
    ␊
      todo␊
    ␊
    ␊
    ␊
    ␊
      Failed Tests: There were 2 failures␊
    ␊
        fail␊
    ␊
          ✖ fail␊
    ␊
    ␊
        todo␊
    ␊
          ✖ todo # TODO␊
    ␊
    ␊
      total:     6␊
      passing:   4␊
      failing:   2␊
      duration:  ␊
    ␊
    ␊
    `

## tap-spec - pass

> Snapshot 1

    `␊
      passing␊
    ␊
        ✔ passing␊
    ␊
    ␊
      total:     1␊
      passing:   1␊
      duration:  ␊
    ␊
    `

## tap-spec - pass-fail

> Snapshot 1

    `␊
      passing␊
    ␊
        ✔ passing␊
    ␊
      fail␊
    ␊
    ␊
        ✖ fail␊
        -------␊
          actual: 1␊
          expected: 2␊
          operator: ===␊
          name: Error␊
          message: error␊
          at: 'fn (test.js:1:2)'␊
    ␊
    ␊
    ␊
    ␊
      Failed Tests: There was 1 failure␊
    ␊
        fail␊
    ␊
          ✖ fail␊
    ␊
    ␊
      total:     2␊
      passing:   1␊
      failing:   1␊
      duration:  ␊
    ␊
    ␊
    `

## tap-spec - pass-with-multiple-comments

> Snapshot 1

    `␊
      pass with comment␊
    ␊
        ✔ pass with comment␊
          * Hello␊
          * Bonjour␊
    ␊
    ␊
      total:     1␊
      passing:   1␊
      duration:  ␊
    ␊
    `

## tap-spec - pass-with-single-comment

> Snapshot 1

    `␊
      pass with comment␊
    ␊
        ✔ pass with comment␊
          * Hello␊
    ␊
    ␊
      total:     1␊
      passing:   1␊
      duration:  ␊
    ␊
    `

## tap-spec - skip

> Snapshot 1

    `␊
      skip␊
    ␊
        ✔ skip # SKIP␊
    ␊
    ␊
      total:     1␊
      passing:   1␊
      duration:  ␊
    ␊
    `

## tap-spec - todo

> Snapshot 1

    `␊
      todo␊
    ␊
    ␊
    ␊
    ␊
      Failed Tests: There was 1 failure␊
    ␊
        todo␊
    ␊
          ✖ todo # TODO␊
    ␊
    ␊
      total:     1␊
      passing:   0␊
      failing:   1␊
      duration:  ␊
    ␊
    `

## tap-summary - fail

> Snapshot 1

    `␊
    [33m# Tests␊
    [0m␊
    [G[K# fail [pass: 0, fail: 0, duration: ][G[K# fail [pass: 0, fail: 1, duration: ][G[31m[K✖ fail [pass: 0, fail: 1, duration: ][0m␊
    ␊
    [33m# Summary␊
    [0m␊
    [36mduration: [0m␊
    [36mplanned: 1[0m␊
    [36massertions: 1[0m␊
    [36mpass: 0[0m␊
    [31mfail: 1[0m␊
    ␊
    [33m# Fails␊
    [0m␊
    [36m[4m## fail[0m[0m␊
    [31m  ✖ fail[0m␊
    [36m    actual: 1␊
        expected: 2␊
        operator: ===␊
        name: Error␊
        message: error␊
        at: 'fn (test.js:1:2)'[0m␊
    ␊
    `

## tap-summary - fail-without-error

> Snapshot 1

    `␊
    [33m# Tests␊
    [0m␊
    [G[K# fail [pass: 0, fail: 0, duration: ][G[K# fail [pass: 0, fail: 1, duration: ][G[31m[K✖ fail [pass: 0, fail: 1, duration: ][0m␊
    ␊
    [33m# Summary␊
    [0m␊
    [36mduration: [0m␊
    [36mplanned: 1[0m␊
    [36massertions: 1[0m␊
    [36mpass: 0[0m␊
    [31mfail: 1[0m`

## tap-summary - mixed

> Snapshot 1

    `␊
    [33m# Tests␊
    [0m␊
    [G[K# passing [pass: 0, fail: 0, duration: ][G[K# passing [pass: 1, fail: 0, duration: ][G[32m[K✔ passing [pass: 1, fail: 0, duration: ][0m␊
    [G[K# fail [pass: 0, fail: 0, duration: ][G[K# fail [pass: 0, fail: 1, duration: ][G[31m[K✖ fail [pass: 0, fail: 1, duration: ][0m␊
    [G[K# pass with comment [pass: 0, fail: 0, duration: ][G[K# pass with comment [pass: 1, fail: 0, duration: ][G[32m[K✔ pass with comment [pass: 1, fail: 0, duration: ][0m␊
    [G[K# pass with comment [pass: 0, fail: 0, duration: ][G[K# pass with comment [pass: 1, fail: 0, duration: ][G[32m[K✔ pass with comment [pass: 1, fail: 0, duration: ][0m␊
    [G[K# skip [pass: 0, fail: 0, duration: ][G[K# skip [pass: 1, fail: 0, duration: ][G[32m[K✔ skip [pass: 1, fail: 0, duration: ][0m␊
    [G[K# todo [pass: 0, fail: 0, duration: ][G[K# todo [pass: 0, fail: 1, duration: ][G[31m[K✖ todo [pass: 0, fail: 1, duration: ][0m␊
    ␊
    [33m# Summary␊
    [0m␊
    [36mduration: [0m␊
    [36mplanned: 6[0m␊
    [36massertions: 6[0m␊
    [32mpass: 4[0m␊
    [31mfail: 2[0m`

## tap-summary - pass

> Snapshot 1

    `␊
    [33m# Tests␊
    [0m␊
    [G[K# passing [pass: 0, fail: 0, duration: ][G[K# passing [pass: 1, fail: 0, duration: ][G[32m[K✔ passing [pass: 1, fail: 0, duration: ][0m␊
    ␊
    [33m# Summary␊
    [0m␊
    [36mduration: [0m␊
    [36mplanned: 1[0m␊
    [36massertions: 1[0m␊
    [32mpass: 1[0m␊
    [36mfail: 0[0m␊
    `

## tap-summary - pass-fail

> Snapshot 1

    `␊
    [33m# Tests␊
    [0m␊
    [G[K# passing [pass: 0, fail: 0, duration: ][G[K# passing [pass: 1, fail: 0, duration: ][G[32m[K✔ passing [pass: 1, fail: 0, duration: ][0m␊
    [G[K# fail [pass: 0, fail: 0, duration: ][G[K# fail [pass: 0, fail: 1, duration: ][G[31m[K✖ fail [pass: 0, fail: 1, duration: ][0m␊
    ␊
    [33m# Summary␊
    [0m␊
    [36mduration: [0m␊
    [36mplanned: 2[0m␊
    [36massertions: 2[0m␊
    [32mpass: 1[0m␊
    [31mfail: 1[0m␊
    ␊
    [33m# Fails␊
    [0m␊
    [36m[4m## fail[0m[0m␊
    [31m  ✖ fail[0m␊
    [36m    actual: 1␊
        expected: 2␊
        operator: ===␊
        name: Error␊
        message: error␊
        at: 'fn (test.js:1:2)'[0m␊
    ␊
    `

## tap-summary - pass-with-multiple-comments

> Snapshot 1

    `␊
    [33m# Tests␊
    [0m␊
    [G[K# pass with comment [pass: 0, fail: 0, duration: ][G[K# pass with comment [pass: 1, fail: 0, duration: ][G[32m[K✔ pass with comment [pass: 1, fail: 0, duration: ][0m␊
    ␊
    [33m# Summary␊
    [0m␊
    [36mduration: [0m␊
    [36mplanned: 1[0m␊
    [36massertions: 1[0m␊
    [32mpass: 1[0m␊
    [36mfail: 0[0m␊
    ␊
    [33m# Comments␊
    [0m␊
    [36m[4m## pass with comment[0m[0m␊
      * Hello␊
      * Bonjour␊
    `

## tap-summary - pass-with-single-comment

> Snapshot 1

    `␊
    [33m# Tests␊
    [0m␊
    [G[K# pass with comment [pass: 0, fail: 0, duration: ][G[K# pass with comment [pass: 1, fail: 0, duration: ][G[32m[K✔ pass with comment [pass: 1, fail: 0, duration: ][0m␊
    ␊
    [33m# Summary␊
    [0m␊
    [36mduration: [0m␊
    [36mplanned: 1[0m␊
    [36massertions: 1[0m␊
    [32mpass: 1[0m␊
    [36mfail: 0[0m␊
    ␊
    [33m# Comments␊
    [0m␊
    [36m[4m## pass with comment[0m[0m␊
      * Hello␊
    `

## tap-summary - skip

> Snapshot 1

    `␊
    [33m# Tests␊
    [0m␊
    [G[K# skip [pass: 0, fail: 0, duration: ][G[K# skip [pass: 1, fail: 0, duration: ][G[32m[K✔ skip [pass: 1, fail: 0, duration: ][0m␊
    ␊
    [33m# Summary␊
    [0m␊
    [36mduration: [0m␊
    [36mplanned: 1[0m␊
    [36massertions: 1[0m␊
    [32mpass: 1[0m␊
    [36mfail: 0[0m␊
    `

## tap-summary - todo

> Snapshot 1

    `␊
    [33m# Tests␊
    [0m␊
    [G[K# todo [pass: 0, fail: 0, duration: ][G[K# todo [pass: 0, fail: 1, duration: ][G[31m[K✖ todo [pass: 0, fail: 1, duration: ][0m␊
    ␊
    [33m# Summary␊
    [0m␊
    [36mduration: [0m␊
    [36mplanned: 1[0m␊
    [36massertions: 1[0m␊
    [36mpass: 0[0m␊
    [31mfail: 1[0m`