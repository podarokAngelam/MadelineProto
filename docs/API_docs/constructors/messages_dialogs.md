## Constructor: messages\_dialogs  

### Attributes:

| Name     |    Type       | Required |
|----------|:-------------:|---------:|
|dialogs|Array of [Dialog](../types/Dialog.md) | Required|
|messages|Array of [Message](../types/Message.md) | Required|
|chats|Array of [Chat](../types/Chat.md) | Required|
|users|Array of [User](../types/User.md) | Required|


### Type: [messages\_Dialogs](../types/messages\_Dialogs.md)

### Example:


```
$messages_dialogs = ['dialogs' => [Dialog], 'messages' => [Message], 'chats' => [Chat], 'users' => [User], ];
```