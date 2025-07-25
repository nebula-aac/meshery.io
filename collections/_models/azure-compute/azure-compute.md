---
layout: single-page-model
item-type: model
name: Azure Compute
subtitle: Collaborative and visual infrastructure as design for Azure Compute
colorIcon: /assets/images/integration/azure-compute/icons/color/azure-compute-color.svg
whiteIcon: /assets/images/integration/azure-compute/icons/white/azure-compute-white.svg
docURL: https://docs.meshery.io/extensibility/integrations/azure-compute
description: 
category: Provisioning
subcategory: Compute
registrant: GitHub
components: 
- name: disk-access
  colorIcon: assets/images/integration/azure-compute/components/disk-access/icons/color/disk-access-color.svg
  whiteIcon: assets/images/integration/azure-compute/components/disk-access/icons/white/disk-access-white.svg
  description: 
- name: disk-encryption-set
  colorIcon: assets/images/integration/azure-compute/components/disk-encryption-set/icons/color/disk-encryption-set-color.svg
  whiteIcon: assets/images/integration/azure-compute/components/disk-encryption-set/icons/white/disk-encryption-set-white.svg
  description: 
- name: disk
  colorIcon: assets/images/integration/azure-compute/components/disk/icons/color/disk-color.svg
  whiteIcon: assets/images/integration/azure-compute/components/disk/icons/white/disk-white.svg
  description: 
- name: image
  colorIcon: assets/images/integration/azure-compute/components/image/icons/color/image-color.svg
  whiteIcon: assets/images/integration/azure-compute/components/image/icons/white/image-white.svg
  description: 
- name: snapshot
  colorIcon: assets/images/integration/azure-compute/components/snapshot/icons/color/snapshot-color.svg
  whiteIcon: assets/images/integration/azure-compute/components/snapshot/icons/white/snapshot-white.svg
  description: 
- name: virtual-machine
  colorIcon: assets/images/integration/azure-compute/components/virtual-machine/icons/color/virtual-machine-color.svg
  whiteIcon: assets/images/integration/azure-compute/components/virtual-machine/icons/white/virtual-machine-white.svg
  description: 
- name: virtual-machine-scale-set
  colorIcon: assets/images/integration/azure-compute/components/virtual-machine-scale-set/icons/color/virtual-machine-scale-set-color.svg
  whiteIcon: assets/images/integration/azure-compute/components/virtual-machine-scale-set/icons/white/virtual-machine-scale-set-white.svg
  description: 
- name: virtual-machine-scale-sets-extension
  colorIcon: assets/images/integration/azure-compute/components/virtual-machine-scale-sets-extension/icons/color/virtual-machine-scale-sets-extension-color.svg
  whiteIcon: assets/images/integration/azure-compute/components/virtual-machine-scale-sets-extension/icons/white/virtual-machine-scale-sets-extension-white.svg
  description: 
- name: virtual-machines-extension
  colorIcon: assets/images/integration/azure-compute/components/virtual-machines-extension/icons/color/virtual-machines-extension-color.svg
  whiteIcon: assets/images/integration/azure-compute/components/virtual-machines-extension/icons/white/virtual-machines-extension-white.svg
  description: 
componentsCount: 9
relationships: 
- type: "Parent"
  kind: "Hierarchical"
  description: "A hierarchical inventory relationship in which the configuration of Virtual Machine Scale Set(parent component) is patched with the configuration of Virtual Machine Scale Set Extension(child component). "
- type: "Parent"
  kind: "Hierarchical"
  description: "A hierarchical inventory relationship in which the configuration of Virtual Machine(parent component) is patched with the configuration of Virtual Machine Extension(child component). "
- type: "Non Binding"
  kind: "Edge"
  description: "An edge relationship between DiskEncryptionSet and vault(azure-key-vault)"
- type: "Non Binding"
  kind: "Edge"
  description: "An edge relationship between Image and Snapshot(azure-compute)"
relationshipsCount: 4
featureList: [
  "Drag-n-drop cloud native infrastructure designer to configure, model, and deploy your workloads.",
  "Invite anyone to review and make changes to your private designs.",
  "Ongoing synchronization of Kubernetes configuration and changes across any number of clusters."
]
howItWorks: "Collaborative Infrastructure as Design"
howItWorksDetails: "Collaboratively manage infrastructure with your coworkers synchronously sharing the same designs."
---
