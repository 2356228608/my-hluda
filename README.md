# 2. 检出官方 Frida 源码
      - name: Checkout Frida Source
        uses: actions/checkout@v4
        with:
          repository: 'frida/frida'
          ref: '17.x.x'  # <-- 以后想更新成什么版本，直接改这里
          path: frida
          submodules: recursive
