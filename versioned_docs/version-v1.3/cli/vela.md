---
title: CLI Commands
---


## Getting Started

* [vela env](vela_env)	 - Manage environments for vela applications to run.
* [vela init](vela_init)	 - Create scaffold for vela application.
* [vela up](vela_up)	 - Deploy one application

 Deploy one application based on local files or re-deploy an existing application. With the -n/--namespace flag, you can choose the location of the target application.

 To apply application from file, use the -f/--file flag to specify the application file location.

 To give a particular version to this deploy, use the -v/--publish-version flag. When you are deploying an existing application, the version name must be different from the current name. You can also use a history revision for the deploy and override the current application by using the -r/--revision flag.
* [vela show](vela_show)	 - Show the reference doc for component, trait or workflow types.

## Managing Applications

* [vela ls](vela_ls)	 - List all vela applications.
* [vela status](vela_status)	 - Show status of vela application.
* [vela delete](vela_delete)	 - Delete an application.
* [vela exec](vela_exec)	 - Execute command inside container based vela application.
* [vela port-forward](vela_port-forward)	 - Forward local ports to container/service port of vela application.
* [vela logs](vela_logs)	 - Tail logs for vela application.
* [vela live-diff](vela_live-diff)	 - Compare application and revisions
* [vela dry-run](vela_dry-run)	 - Dry-run application locally, render the Kubernetes resources as result to stdout.
* [vela revision](vela_revision)	 - Manage KubeVela Application Revisions

## Continuous Delivery

* [vela cluster](vela_cluster)	 - Manage Kubernetes Clusters for Continuous Delivery.
* [vela workflow](vela_workflow)	 - Operate the Workflow during Application Delivery.

## Managing Extension

* [vela addon](vela_addon)	 - Manage addons for extension.
* [vela uischema](vela_uischema)	 - Manage UI schema for addons.
* [vela def](vela_def)	 - Manage X-Definitions for extension.
* [vela registry](vela_registry)	 - Manage Registry of X-Definitions for extension.
* [vela provider](vela_provider)	 - Authenticate Terraform Cloud Providers by managing Terraform Controller Providers with its credential secret
* [vela component](vela_component)	 - List component types installed and discover more in registry.
* [vela trait](vela_trait)	 - List trait types installed and discover more in registry.

## Others

* [vela uninstall](vela_uninstall)	 - Uninstalls KubeVela from a Kubernetes cluster.
* [vela install](vela_install)	 - The Kubevela CLI allows installing Kubevela on any Kubernetes derivative to which your kube config is pointing to.
* [vela completion](vela_completion)	 - Output shell completion code for the specified shell (bash or zsh). 
The shell code must be evaluated to provide interactive completion of vela commands.
* [vela export](vela_export)	 - Export deploy manifests from appfile or application.
* [vela version](vela_version)	 - Prints vela build version information.

###### Auto generated by [script in KubeVela](https://github.com/oam-dev/kubevela/tree/master/hack/docgen).