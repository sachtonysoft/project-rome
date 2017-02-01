# Platform.IAuthCodeHandler interface
Provides a method for getting an authorization token, as part of the platform initialization process.

## Syntax
`public interface IAuthCodeHandler`

## Public methods

### onAuthCodeFetched
Called when the Remote Systems platform is initializing and must acquire a new authorization code.

`void onAuthCodeFetched(String authCode)`

**Parameters**
*authCode* - the previous authorization code that the system will attempt to refresh