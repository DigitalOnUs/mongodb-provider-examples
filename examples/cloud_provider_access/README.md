### Example

The cloud_provider_access resource is now divided into 
-> cloud provider access setup
   This resource performs the setup for the given provider, 
   returning the proper config (atlas_aws_account_arn, atlas_assumed_role_external_id)

-> cloud provider access authorization  
   The authorization against a provider role 