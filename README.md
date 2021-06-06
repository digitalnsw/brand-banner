

# brand-banner
Brand banner for NSW Gov websites

## Using via CDN

Include the component in <head>
```
<script src="https://cdn.jsdelivr.net/gh/digitalnsw/brand-banner/component/banner.js" defer></script>
```

## via NPM

TODO

## Usage

### Manual

To add the component to your page manually, before before any containers or other visible content include:

```
<nsw-banner>Department of Customer Service</nsw-banner>
```

### Dynamically

TODO

### Including text

Include your agency or cluster name, not the name of the product or service. _Example: 'Department of Customer Service' not 'Apply for a Paintball venue permit'_

If your website is in the 'Endorsed' category, you don't need to include any text.

### max-width

The NSW Government Waratah logo should align to the left side of your content area, and doesn't react to breakpoints. For websites using the Design System this will happen automatically. If you're not using the design system, set the width of your content area using the options below.

## Options

| Property  | Notes                                                                       | Default | Added |
|-----------|-----------------------------------------------------------------------------|---------|-------|
| max-width | Use number + unit, as css e.g. `max-width="75rem"` or `max-width="500px"`   | 75rem   | 0.1.0 |
| theme     | One of: <ul><li>white</li><li>off-white</li><li>blue</li><li>dark</li></ul> | white   | 0.2.0 |

### Example

```
<nsw-banner max-width="900px">Department of Education</nsw-banner>
```
