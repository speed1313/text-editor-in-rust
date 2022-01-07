# text-editor in Rust

# terminalの仕組み
stdoutが出力バッファであり, それを捨てることでタイプした文字を出力しない, または好きな位置に出力するようにできる.

# キーボードの読み取り
各Keyの数値を読み取り, cntrol+Qならexitするようにする.
