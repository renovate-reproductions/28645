# 28645

## Current behavior

```diff
- uses: "actions/setup-java@387ac29b308b003ca37ba93a6cab5eb57c8f5f93" # ratchet:actions/setup-java@v4
+ uses: "actions/setup-java@99b8673ff64fbf99d8d325f52d9a5bdedb8483e9" # v4
```

Renovate strips the `ratchet:actions/setup-java@` part.

## Expected behavior

```diff
- uses: "actions/setup-java@387ac29b308b003ca37ba93a6cab5eb57c8f5f93" # ratchet:actions/setup-java@v4
+ uses: "actions/setup-java@99b8673ff64fbf99d8d325f52d9a5bdedb8483e9" # ratchet:actions/setup-java@v4
```

Renovate keeps the `ratchet:actions/setup-java@` part.

## Link to the Renovate issue or Discussion

[Renovate issue 28645 on GitHub](https://github.com/renovatebot/renovate/issues/28645)
