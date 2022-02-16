See **[swank-description.markdown](swank-description.markdown)** for protocol description.

---

This is an attempt at a minimal client for swank.

Build using Leiningen.

Usage is simple:

    java -cp swank_client.jar swank_client.core -s host_name (localhost) -p port_name (4005) -d debug-mode? (false)

You should be provided with a very simple REPL. This was
designed for use with clojure-swank, but should would with
any version of swank with some limitations.
