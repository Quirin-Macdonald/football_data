## Make sure you have a SSH-Key to make a connection between your local machine and github

  ## On Windows:

  Open 'PowerShell' and use 'ssh-keygen -o -t rsa' to generate a SSH-Key on your machine

  ## Got to Github and add the key

  1. On github.com, click on your avatar on the upper right and select 'Settings' in the menue
  2. In the explorer pane, use the link 'SSH and GPG key'
  3. Click on the green button 'New SSH key'
  4. On your local machine, open the - newly generated - public key 'id_rsa_.pub' with a text editor (Sublime f.e.), which is usually to be found
  under C:\Users\{Your User Name}\.ssh
  5. Copy the content to the clipboard
  6. Name the Key under 'Title' and paste the copied content into 'Key'
  7. Click on 'Add SSH key'

