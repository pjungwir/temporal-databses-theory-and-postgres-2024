all: star_schema.png temporal_products.png products_rows.png products_rows_ranges.png products_rows_ranges_invalid.png products_timeline.png variants_rows.png variants_rows_ranges.png reservations.png reservations_joined.png reservations_timeline.png reservations_timeline_joined.png products_insert_timeline.png products_insert_timeline_okay.png products_insert_timeline_coalesced.png products_insert_timeline_coalescandum.png products_update_timeline.png products_update_timeline_result.png products_update_2_timeline.png products_update_2_timeline_result.png products_delete_timeline.png products_delete_timeline_result.png products_upsert_timeline.png products_upsert_timeline_result.png products_upsert_timeline_result2.png

%.png: %.txt
	ditaa -o -E $<

.PHONY: all
