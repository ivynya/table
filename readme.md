# table <br/>
> [!NOTE]
> This is a fork of [rodaine/table](https://github.com/rodaine/table). It adds the ability to specify a custom formatter for any column, not just the first one. Use `.WithColumnFormatter(i int, f Formatter)` where `i` is less than the number of headers in the created table. I needed this feature quickly, and I would recommend using the original package instead of this fork.

## License

table is released under the MIT License (Expat). See the [full license](https://github.com/rodaine/table/blob/master/license).
