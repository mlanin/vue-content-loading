# Presets

### Facebook

<color-switch>
  <template slot-scope="props">
    <vcl-facebook :primary="props.primary" :secondary="props.secondary" />
  </template>
</color-switch>

### Instagram

<color-switch>
  <template slot-scope="props">
    <vcl-instagram :primary="props.primary" :secondary="props.secondary" />
  </template>
</color-switch>

### Code

<color-switch>
  <template slot-scope="props">
    <vcl-code :primary="props.primary" :secondary="props.secondary" />
  </template>
</color-switch>

### List

<color-switch>
  <template slot-scope="props">
    <vcl-list :primary="props.primary" :secondary="props.secondary" />
  </template>
</color-switch>

### Bullet List

| Custom Prop | Type   | Default | Description      |
|:-----------:|:------:|:-------:|:----------------:|
| rows        | Number | 5       | The list rows    |

<color-switch>
  <template slot-scope="props">
    <vcl-bullet-list :primary="props.primary" :secondary="props.secondary" :rows="5" />
  </template>
</color-switch>

### Twitch

<color-switch>
  <template slot-scope="props">
    <vcl-twitch :primary="props.primary" :secondary="props.secondary" />
  </template>
</color-switch>
