## 0.5.2
 * Minor change to the cli! function so that, in addition to the data that it already returned, it now also returns a string representation of a banner/usage summary.  Callers can use this to display a help message if additional validation of the cli args fails.
 * Utility functions added to ssl namespace that allow creation of an SSLContext or a KeyStore/TrustStore directly from the pem files. 
 * Added some JSON utility functions
 * Added a deep-merge utility function
