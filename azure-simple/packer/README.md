Included Packer configurations scripts to create the WSO2 Enterprise Integrator Azure machine image. Later this builds Packer image is been referred by the Terraform scripts for provision for Enterprise Integrator 2 node setup.
Azure subscription details are included in "variables.json".

Packer Directories and Files
----------------

`ansible-apim/` - 
    included relevant terraform scripts of database server and databases creation for Enterprise Integrator product.

`scripts/` - 
    included relevant Enterprise Integrator runtime configurations and clean up scripts
    
`dbscripts/` - 
    included relevant Enterprise Integrator database schemas and tables files
    
`centos-base.json` - 
    contained relavant packer configurations for build the Azure machine image
    
`Vagrantfile` - 
    contained relavant vagrant configurations for test the Ansible playbook changes in locally
