# Wikidata-Example-Queries

Repository holding all WDQS "example" queries - See the `all_examples` subdirectory
 * The examples were extracted from the following pages:
   * https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/queries/examples
   * https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/queries/examples/advanced
   * https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/queries/examples/human
   * https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/queries/examples/maintenance
 
With their rewrites when migrated to QLever - See the `rewritten_examples` subdirectory

With reports from the rewriter tool - See the `rewritten_examples/rewrite_summaries` subdirectory
   * The reports detail how many queries were rewritten or did not need rewriting (indicated by a comment in the first line of the output - "# rewrite_status: rewritten" or "# rewrite_status: unchanged")
   * And the specific queries that failed to be rewritten, classified by the specific issue that caused the failure

Note that a WIP "rewriter tool" was used to generate the rewritten queries. It is found at https://gitlab.wikimedia.org/repos/wikidata-platform/wikidata-query-rewriter.
