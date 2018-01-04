# Snapshot report for `src/parser/__tests__/expression-spec.js`

The actual snapshot is saved in `expression-spec.js.snap`.

Generated by [AVA](https://ava.li).

## array: offset is compound expression

> Snapshot 1

    {
      Type: 'BinaryExpression',
      meta: [],
      params: [
        {
          Type: 'Identifier',
          meta: [],
          params: [],
          range: [
            {
              col: 0,
              line: 1,
            },
            {
              col: 1,
              line: 1,
            },
          ],
          type: null,
          value: 'a',
        },
        {
          Type: 'BinaryExpression',
          meta: [],
          params: [
            {
              Type: 'ArraySubscript',
              meta: [],
              params: [
                {
                  Type: 'Identifier',
                  meta: [],
                  params: [],
                  range: [
                    {
                      col: 4,
                      line: 1,
                    },
                    {
                      col: 5,
                      line: 1,
                    },
                  ],
                  type: null,
                  value: 'b',
                },
                {
                  Type: 'BinaryExpression',
                  meta: [],
                  params: [
                    {
                      Type: 'Constant',
                      meta: [],
                      params: [],
                      range: [
                        {
                          col: 6,
                          line: 1,
                        },
                        {
                          col: 7,
                          line: 1,
                        },
                      ],
                      type: 'i32',
                      value: '1',
                    },
                    {
                      Type: 'Constant',
                      meta: [],
                      params: [],
                      range: [
                        {
                          col: 10,
                          line: 1,
                        },
                        {
                          col: 11,
                          line: 1,
                        },
                      ],
                      type: 'i32',
                      value: '1',
                    },
                  ],
                  range: [
                    undefined,
                    {
                      col: 12,
                      line: 1,
                    },
                  ],
                  type: null,
                  value: '+',
                },
              ],
              range: [
                undefined,
                {
                  col: 12,
                  line: 1,
                },
              ],
              type: null,
              value: 'b',
            },
            {
              Type: 'Constant',
              meta: [],
              params: [],
              range: [
                {
                  col: 15,
                  line: 1,
                },
                {
                  col: 16,
                  line: 1,
                },
              ],
              type: 'i32',
              value: '5',
            },
          ],
          range: [
            undefined,
            {
              col: 16,
              line: 1,
            },
          ],
          type: null,
          value: '*',
        },
      ],
      range: [
        undefined,
        {
          col: 16,
          line: 1,
        },
      ],
      type: null,
      value: '+',
    }

## array: offset is constant

> Snapshot 1

    {
      Type: 'BinaryExpression',
      meta: [],
      params: [
        {
          Type: 'ArraySubscript',
          meta: [],
          params: [
            {
              Type: 'Identifier',
              meta: [],
              params: [],
              range: [
                {
                  col: 0,
                  line: 1,
                },
                {
                  col: 1,
                  line: 1,
                },
              ],
              type: null,
              value: 'b',
            },
            {
              Type: 'Constant',
              meta: [],
              params: [],
              range: [
                {
                  col: 2,
                  line: 1,
                },
                {
                  col: 3,
                  line: 1,
                },
              ],
              type: 'i32',
              value: '1',
            },
          ],
          range: [
            undefined,
            {
              col: 4,
              line: 1,
            },
          ],
          type: null,
          value: 'b',
        },
        {
          Type: 'Constant',
          meta: [],
          params: [],
          range: [
            {
              col: 7,
              line: 1,
            },
            {
              col: 8,
              line: 1,
            },
          ],
          type: 'i32',
          value: '5',
        },
      ],
      range: [
        undefined,
        {
          col: 8,
          line: 1,
        },
      ],
      type: null,
      value: '+',
    }

## sequence, of compound expressions

> Snapshot 1

    {
      Type: 'Sequence',
      meta: [],
      params: [
        {
          Type: 'Constant',
          meta: [],
          params: [],
          range: [
            {
              col: 0,
              line: 1,
            },
            {
              col: 1,
              line: 1,
            },
          ],
          type: 'i32',
          value: '1',
        },
        {
          Type: 'BinaryExpression',
          meta: [],
          params: [
            {
              Type: 'Constant',
              meta: [],
              params: [],
              range: [
                {
                  col: 3,
                  line: 1,
                },
                {
                  col: 4,
                  line: 1,
                },
              ],
              type: 'i32',
              value: '1',
            },
            {
              Type: 'Constant',
              meta: [],
              params: [],
              range: [
                {
                  col: 7,
                  line: 1,
                },
                {
                  col: 8,
                  line: 1,
                },
              ],
              type: 'i32',
              value: '1',
            },
          ],
          range: [
            undefined,
            {
              col: 9,
              line: 1,
            },
          ],
          type: null,
          value: '+',
        },
        {
          Type: 'BinaryExpression',
          meta: [],
          params: [
            {
              Type: 'BinaryExpression',
              meta: [],
              params: [
                {
                  Type: 'Constant',
                  meta: [],
                  params: [],
                  range: [
                    {
                      col: 11,
                      line: 1,
                    },
                    {
                      col: 12,
                      line: 1,
                    },
                  ],
                  type: 'i32',
                  value: '2',
                },
                {
                  Type: 'Constant',
                  meta: [],
                  params: [],
                  range: [
                    {
                      col: 15,
                      line: 1,
                    },
                    {
                      col: 16,
                      line: 1,
                    },
                  ],
                  type: 'i32',
                  value: '3',
                },
              ],
              range: [
                undefined,
                {
                  col: 17,
                  line: 1,
                },
              ],
              type: null,
              value: '*',
            },
            {
              Type: 'Constant',
              meta: [],
              params: [],
              range: [
                {
                  col: 20,
                  line: 1,
                },
                {
                  col: 21,
                  line: 1,
                },
              ],
              type: 'i32',
              value: '2',
            },
          ],
          range: [
            undefined,
            {
              col: 22,
              line: 1,
            },
          ],
          type: null,
          value: '/',
        },
        {
          Type: 'Constant',
          meta: [],
          params: [],
          range: [
            {
              col: 23,
              line: 1,
            },
            {
              col: 25,
              line: 1,
            },
          ],
          type: 'i32',
          value: '11',
        },
      ],
      range: [
        undefined,
        {
          col: 25,
          line: 1,
        },
      ],
      type: null,
      value: ',',
    }

## sequence, of constants

> Snapshot 1

    {
      Type: 'Sequence',
      meta: [],
      params: [
        {
          Type: 'Constant',
          meta: [],
          params: [],
          range: [
            {
              col: 0,
              line: 1,
            },
            {
              col: 1,
              line: 1,
            },
          ],
          type: 'i32',
          value: '1',
        },
        {
          Type: 'Constant',
          meta: [],
          params: [],
          range: [
            {
              col: 3,
              line: 1,
            },
            {
              col: 4,
              line: 1,
            },
          ],
          type: 'i32',
          value: '2',
        },
        {
          Type: 'Constant',
          meta: [],
          params: [],
          range: [
            {
              col: 6,
              line: 1,
            },
            {
              col: 7,
              line: 1,
            },
          ],
          type: 'i32',
          value: '3',
        },
      ],
      range: [
        undefined,
        {
          col: 7,
          line: 1,
        },
      ],
      type: null,
      value: ',',
    }