# Hello world docker action

This action prints "Hello World" to the log or "Hello" + the name of a person to greet.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-docker-action@master
with:
  who-to-greet: 'Mona the Octocat'
```
