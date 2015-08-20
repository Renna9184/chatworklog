# GoodbyeChatwork

This is Chatwork(chatwork.com) log exporter. This can be used also when you can not use API.

## Installation

    $ gem install goobye_chatwork

## Usage

show chat room list (output: room_id room_name count)

    $ goodbye_chatwork -i tan@mrfusion.co.jp -p tantan01
    11111 chatroom1 24
    11112 chatroom1 42

export logs (chat logs only: -e option)

    $ goodbye_chatwork -i tan@mrfusion.co.jp -p tantan01 -e #!rid21344070

export logs (chat logs and attachment files: -x option)

    $ goodbye_chatwork -i tan@mrfusion.co.jp -p tantan01 -x #!rid21344070

## Information

Copyright (c) 2014 swdyh
MIT License
https://github.com/swdyh/goodbye_chatwork