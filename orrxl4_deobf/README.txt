python main.py <protector-url | id | file> [-o out.lua] [--follow] [-v]

orrxl4/fetch.py        fetch with client-profile rotation and retries until the ORRXL4 header appears (never accepts HTML)
orrxl4/layers.py       peels nested loader layers by executing them in the sandbox with loadstring hooked
orrxl4/sandbox.py      runs a loader with no host access and a time limit
orrxl4/lua/            lexer, parser, closure-compiling interpreter, restricted stdlib
orrxl4/fastpaths.py    verified native RC4/XOR shortcuts, selected by AST fingerprint
orrxl4/reconstruct.py  removes comments and junk, renames obfuscated names, pretty-prints
orrxl4/pipeline.py     fetch -> peel -> reconstruct -> optional follow of HttpGet urls
tests/                 python -m unittest discover -s tests -t .
