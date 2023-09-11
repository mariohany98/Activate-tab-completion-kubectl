# Enabling Tab Completion for `kubectl` on Ubuntu

Tab completion for `kubectl` allows for faster and more efficient interaction with your Kubernetes cluster. If you're on Ubuntu and facing issues with tab completion, follow these steps to enable it.

## Prerequisites

- Ubuntu Linux
- `kubectl` installed
- Bash 

## Instructions

1- **Run the following command**
   
        echo 'source <(kubectl completion bash)' >> ~/.bashrc
   
2- **Reload Your Shell Configuration**
   
        source ~/.bashrc
   
3- **Test Tab Completion**
   
        kubectl

## Note
**For helm use the following command**
         echo 'source <(helm completion bash)' >> ~/.bashrc
