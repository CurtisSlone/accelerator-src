# TEST TF WORKSPACES Code
Using Linux to sort workspaces
### Current Workspaces

rg1 - simple resource group

rg2 - simple resource group


if [[ "${{ github.event.head_commit.message}}" == *"rg1"* ]]; then
            echo "Found rg1"
          else
            echo "Did not find"
            exit 1
          fi