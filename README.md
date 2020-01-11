# FunctionMonkey-ToDo-MediatR

A small sample demonstrating how to use [Function Monkey](https://functionmonkey.azurefromthetrenches.com) with MediatR. Essentially its the same as a traditional Function Monkey application exception the MediatR interfaces IRequest<> and INotification are used instead of ICommand. Additionally if you examine FunctionAppConfiguration you will see the line:

    .UseMediatR()

This instructs Function Monkey to use MediatR as the mediation framework.

You will also need to add the package FunctionMonkey.MediatR.
