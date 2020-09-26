# HexRaysDeob_Build
HexRaysDeob build with IDA SDK 7.2 và VS 2019.

Đã build cho IDA 32bit và 64bit.

Build từ bản của CarbonBlack, không phải từ bản gốc của Rolf Rolles. 

Họ đã add thêm nhiều obfuscation pattern.

github của CarbonBlack:

https://github.com/carbonblack/HexRaysDeob

github của Rolf Rolles:

https://github.com/RolfRolles/HexRaysDeob

Các bạn dùng IDAPython để chạy plugin này với các args sau: idaapi.load_and_run_plugin("HexRaysDeob", arg)

Hoặc IDC: RunPlugin/load_and_run_plugin("HexRaysDeob", arg)

1. arg = 0xbeef: Unload plugin
2. arg = 0xdead: insert current screen ea function to backlist
3. arg = 0xf001: remove current screen ea function from backlist
4. arg = 2: FixCallsToAllocaProbe
5. arg = 3: ShowMicrocodeExplorer, tương tự như của HexRaysCodeXplorer và nhiều IDAPython plugin khác.

Không hiểu cách dùng thì các bạn chịu khó đọc từ 2 link trên và đọc source.

Cảm ơn

Chân chọng en bét xì ga :D
