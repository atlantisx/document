# Atlantis Admin


<a name="introduction"></a>
## Introduction

## Admin API
Admin API as other API in Atlantis providing a facilities to front-end to communicate and getting data from Atlantis back-end using Ajax or Atlantis Rest library. Example shown below on how to retrieve a user from information using Atlantis Rest library.

	var params = {model:'users', id:'{{ $user->id }}', 'access':'simple'};
	
	$scope.user = Api.get(params);

	console.log($scope.user.email);

### Code API

### User API

## Events

#### Events Trigger for Controller Auth

Event                   | Parameters          | Description
------------------------------------------------------------
auth.login              | $realm, $credential | Trigger upon normal authentication
auth.login.alternative  | $realm, $credential | Trigger when credential email fail valication process
user.registering        | $realm              | 
user.registered         | $user, $realm       |

#### Events Trigger for Controller Admin