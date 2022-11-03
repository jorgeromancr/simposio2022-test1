## Android Deep-linking - Simposio IE 2022 

```markdown
When a clicked link or programmatic request invokes a web URI intent, the Android system tries each of the following actions, in sequential order, until the request succeeds:

1. Open the user's preferred app that can handle the URI, if one is designated.
2. Open the only available app that can handle the URI.
3. Allow the user to select an app from a dialog.

```

## Here some examples:

### Form redirection
[Registration form](https://forms.gle/QLKHJUne9JfS832Z9/)

### Form redirection (Green color)
[Registration form](https://forms.gle/QLKHJUne9JfS832Z9?green)

### Form redirection (Blue color)
[Registration form](https://forms.gle/QLKHJUne9JfS832Z9?blue)

### Form redirection (Custom schema)
[Registration form](konradapp://forms.gle/QLKHJUne9JfS832Z9?blue)


![Image](/img/ucr-banner.png)


For more information see [Android documentation](https://developer.android.com/training/app-links/deep-linking).
