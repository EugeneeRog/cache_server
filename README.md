Use $make for compile:

$erl
1> cache_server:start().

Commands :

gen_server:call(cache_server,{insert,{Key,Value,Time}) for add elements, Time is timer of element living,in milliseconds;

gen_server:call(cache_server,{lookup,{Key}) for search elements;

gen_server:call(cache_server,{cleaning}) for manual clean (only old elements).
