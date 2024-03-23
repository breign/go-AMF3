# Golang AMF v3

as per https://en.wikipedia.org/wiki/Action_Message_Format

works encoding and decoding for all the primitives as well as for dynamic Objects, eg:

    {
        abc: "abc"
        ,dtl: new Date
        ,num: Number(123.456789)
        ,arr: [0,1,2,"lol",3]
        ,int: 1337
    }

I use this for binary websockets.
