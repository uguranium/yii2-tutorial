# Yii2 Rules
### Mail Configration
On the model rules function use this command
> ['email', 'email']

### Required Message
On the model rules function in variable array use the 'message' after the requied. Like this
> ['username', 'required', 'message' => 'Please write user name']

### Too Long or Too Short Validation Meassage
On the model rules function use array like this
> [['username', 'string', 'min' => 2, 'max' => 255, 'tooShort' => 'User name too short', 'tooLong' => 'User name too long']]