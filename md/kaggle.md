# Data set

## Column Name with IDs

- 40 cli
- 41 ili
- 42 hh_cmnty_cli
- 43 nohh_cmnty_cli
- 44 wearing_mask
- 45 travel_outside_state
- 46 work_outside_home
- 47 shop
- 48 restaurant
- 49 spent_time
- 50 large_event
- 51 public_transit
- 52 anxious
- 53 depressed
- 54 felt_isolated
- 55 worried_become_ill
- 56 worried_finances
- 57 tested_positive
- 58 cli.1
- 59 ili.1
- 60 hh_cmnty_cli.1
- 61 nohh_cmnty_cli.1
- 62 wearing_mask.1
- 63 travel_outside_state.1
- 64 work_outside_home.1
- 65 shop.1
- 66 restaurant.1
- 67 spent_time.1
- 68 large_event.1
- 69 public_transit.1
- 70 anxious.1
- 71 depressed.1
- 72 felt_isolated.1
- 73 worried_become_ill.1
- 74 worried_finances.1
- 75 tested_positive.1
- 76 cli.2
- 77 ili.2
- 78 hh_cmnty_cli.2
- 79 nohh_cmnty_cli.2
- 80 wearing_mask.2
- 81 travel_outside_state.2
- 82 work_outside_home.2
- 83 shop.2
- 84 restaurant.2
- 85 spent_time.2
- 86 large_event.2
- 87 public_transit.2
- 88 anxious.2
- 89 depressed.2
- 90 felt_isolated.2
- 91 worried_become_ill.2
- 92 worried_finances.2
- 93 tested_positive.2

## Original Data set results

### Batch Size

- batch size 50  .85278
- batch size 100 .85134 **
- batch size 200 .86139

### Number of Selected Features

- feat 10 .87227
- feat 14 .86159
- feat 15 .86369
- feat 17 .85849
- feat 20 .86158
- feat 23 .85781
- feat 26 .85134 **
- feat 29 .89945

### Normalized Feature

- norm 3.19961

### Train Dev split

- 9:1 .85134 **
- 8:2 .88327

### Mid Layer Size

- hdim 26 .86450
- hdim 39 .86655
- hdim 42 .85742
- hdim 44 .85893
- hdim 45 .86378
- hdim 47 .85134 **
- hdim 52 .86034

### Activation Function Compare

- relu      .85134 **
- rrelu     .86596
- LeakyReLU .85441
- relu6     1.32248
- elu       .85750
- selu      .86277
- silu      .86135

### Activation Extra

- relu only      .85134  **
- relu + norm1d  1.18196
- relu + do 0.1  .86391
- relu + do 0.2  .89644

## Todo

- Mid layer size
