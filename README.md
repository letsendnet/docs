# docs
Pass URL Parameters to Destination URL
You can now pass URL query parameters (utm_source, ref, etc.) from your short link to its destination URL.

If there are any duplicate parameters, the parameter in the short link will override its counterpart in the destination URL.

For example:

letsend.net/oss redirects to destination.com/oss?ref=letsend
letsend.net/oss?ref=my-domain.com redirects to destination.com/oss?ref=my-domain.com
