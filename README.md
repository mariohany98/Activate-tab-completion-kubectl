# Enabling Tab Completion for `kubectl` on Ubuntu

Tab completion for `kubectl` allows for faster and more efficient interaction with your Kubernetes cluster. If you're on Ubuntu and facing issues with tab completion, follow these steps to enable it.

## Prerequisites

- Ubuntu Linux
- `kubectl` installed
- Bash 

## Instructions
   1. **Download the `kubectl` Completion Script**
   
      mkdir -p ~/.kube/completion
      
      kubectl completion bash > ~/.kube/completion/kubectl

     2- **Add the Completion Script Source Line**
   
        source ~/.kube/completion/kubectl
   
     3- **Reload Your Shell Configuration**
   
        source ~/.bashrc
   
     4- **Test Tab Completion**
   
        kubectl
