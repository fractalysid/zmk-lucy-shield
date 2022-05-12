# Lucy

36 key, diodeless, wireless only keyboard

## Pin arrangement

```dts
&kscan0 {
	input-gpios
	= <&pro_micro  7 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro  0 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro  2 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro  3 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro  4 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro  5 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro  6 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro  1 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro  8 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro  9 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro 15 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro 18 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro 19 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro 20 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro 21 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro 14 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro 16 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
		, <&pro_micro 10 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
	<&pro_micro 10 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro  2 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro  5 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro  6 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro  7 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro  8 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro  9 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro  1 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro 11 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro 12 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro 16 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro 17 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro 18 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro 19 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro 15 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro 14 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>,
      <&pro_micro 13 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>
	;
};
```

This `&kscan0` block must be placed outside of any blocks surrounded by curly braces (`{...}`).
