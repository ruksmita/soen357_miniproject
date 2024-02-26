---
title: "SOEN357 - Mini Project"
date: 2024-02-26
---

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="375" height="687" src="https://app.uizard.io/p/2e0eb485/embed" allowfullscreen></iframe>
<script>
    // Wait for the iframe content to load
    document.getElementById('myIframe').onload = function() {
        // Access the contentDocument of the iframe
        var iframeDoc = document.getElementById('myIframe').contentDocument;
        
        // Check if the iframe document is accessible
        if (iframeDoc) {
            // Find and remove elements containing the word "uizard"
            var elements = iframeDoc.querySelectorAll(':contains("uizard")');
            elements.forEach(function(element) {
                element.parentNode.removeChild(element);
            });
        } else {
            console.error('Could not access the iframe content document.');
        }
    };
</script>
