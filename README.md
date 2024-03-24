# Distributed Information Retrieval

This exercise involves creating a distributed system for information retrieval. The system consists of a server and multiple clients. The server acts as an intermediary between the clients, establishing communication through sockets.

## Overview

The system starts with a file on the server side containing people's information, including ID, name, family name, and city of residence. This information is randomly distributed to different clients.

The clients are connected to each other through the server and communicate and exchange data with each other. None of the clients have a direct relationship with each other, and all communication and data exchange occurs through the server.

The server acts as the medium for the clients' requests. When a client requests information about a person or persons from different clients, the server retrieves this information from the relevant client(s) and returns it to the requesting client.

## Output

The information returned by the server to the requesting client is printed in the output.

## Note

This exercise is designed to help you understand the workings of a distributed system and the role of a server in managing communication between clients. It also provides practical experience in working with sockets and handling data exchange in a distributed environment.
