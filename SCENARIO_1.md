# Scenario 1

While you are traveling on a train to Hamburg, the guy next to you makes a call to his manager. He explains how quickly and easily he created multiple 1-node-kubeadm clusters on the cloud. Because he was talking about Kubernetes, you started eavesdropping.

On his screen, you see some IP addresses. As you are very good with numbers, you memorize one of them unintentionally.

During the conversation, he says the SSH Key to access the VM is added to the cluster as a secret and mounted by a running Pod.

You can't help yourself by getting the key and logging in to the server. Together with the SSH key, you will also find the first flag!


> Hint: You can connect to the VM via this command after getting the SSH key: `ssh -i <key_file> ubuntu@${IP}`

[Introduction](./README.md) | [Scenario 2](./SCENARIO_2.md)