# aeson-yak
*A Haskell helper library to help aeson parse and output JSON elements that may or may not be a list, or exist.*

---
According to the standard promoted by Schema.org, the following are all legally the same object:

    { field: [data1, data2] }
    { field: data }
    { }

This library provides an intermediary data type and supporting functions to shave that stupid yak.
