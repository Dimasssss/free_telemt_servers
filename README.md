# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 11:15:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 48408.6 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1143020
telemt_connections_bad_total 96857
telemt_connections_current 1512
telemt_connections_me_current 1512
telemt_handshake_timeouts_total 39987
telemt_upstream_connect_attempt_total 9307
telemt_upstream_connect_success_total 9145
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 9307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 8587
telemt_me_reconnect_success_total 6718
telemt_me_reader_eof_total 7103
telemt_me_idle_close_by_peer_total 7100
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 474482
telemt_me_route_drop_channel_closed_total 176
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 890994
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4955
telemt_desync_full_logged_total 1514
telemt_desync_suppressed_total 3441
telemt_desync_frames_bucket_total{bucket="1_2"} 1622
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 1526
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6872
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 6697
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 884932
telemt_user_connections_current{user="hello"} 1512
telemt_user_octets_from_client{user="hello"} 13370707252 (12.45 GB)
telemt_user_octets_to_client{user="hello"} 271558186084 (252.91 GB)
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 48412.4 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3028592
telemt_connections_bad_total 177463
telemt_connections_current 3723
telemt_connections_me_current 3723
telemt_handshake_timeouts_total 57930
telemt_upstream_connect_attempt_total 9200
telemt_upstream_connect_success_total 9033
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 9200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 12653
telemt_me_reconnect_success_total 6581
telemt_me_reader_eof_total 7087
telemt_me_idle_close_by_peer_total 7086
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 2072646
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2555869
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10387
telemt_desync_full_logged_total 3473
telemt_desync_suppressed_total 6914
telemt_desync_frames_bucket_total{bucket="1_2"} 2000
telemt_desync_frames_bucket_total{bucket="3_10"} 4096
telemt_desync_frames_bucket_total{bucket="gt_10"} 4291
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6887
telemt_me_refill_failed_total 189
telemt_me_writer_restored_same_endpoint_total 6559
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 2555490
telemt_user_connections_current{user="hello"} 3723
telemt_user_octets_from_client{user="hello"} 35282366412 (32.86 GB)
telemt_user_octets_to_client{user="hello"} 808094765944 (752.60 GB)
telemt_user_unique_ips_current{user="hello"} 1301
telemt_user_unique_ips_recent_window{user="hello"} 561
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 48411.3 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2415789
telemt_connections_bad_total 282098
telemt_connections_current 3237
telemt_connections_me_current 3237
telemt_handshake_timeouts_total 50883
telemt_upstream_connect_attempt_total 8717
telemt_upstream_connect_success_total 8717
telemt_upstream_connect_attempts_per_request{bucket="1"} 8717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 7457
telemt_me_reconnect_success_total 6263
telemt_me_reader_eof_total 6644
telemt_me_idle_close_by_peer_total 6643
telemt_me_route_drop_no_conn_total 1518031
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1902412
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7970
telemt_desync_full_logged_total 2536
telemt_desync_suppressed_total 5434
telemt_desync_frames_bucket_total{bucket="1_2"} 1786
telemt_desync_frames_bucket_total{bucket="3_10"} 2945
telemt_desync_frames_bucket_total{bucket="gt_10"} 3239
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6407
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6247
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 1900226
telemt_user_connections_current{user="hello"} 3237
telemt_user_octets_from_client{user="hello"} 26702359712 (24.87 GB)
telemt_user_octets_to_client{user="hello"} 809084174012 (753.52 GB)
telemt_user_unique_ips_current{user="hello"} 1106
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 48462.7 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2389974
telemt_connections_bad_total 128549
telemt_connections_current 3055
telemt_connections_me_current 3055
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 62072
telemt_upstream_connect_attempt_total 17008
telemt_upstream_connect_success_total 16841
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 17008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10562
telemt_me_reconnect_success_total 6225
telemt_me_reader_eof_total 6630
telemt_me_idle_close_by_peer_total 6629
telemt_me_route_drop_no_conn_total 1219830
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1815684
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6649
telemt_desync_full_logged_total 2241
telemt_desync_suppressed_total 4408
telemt_desync_frames_bucket_total{bucket="1_2"} 1406
telemt_desync_frames_bucket_total{bucket="3_10"} 2577
telemt_desync_frames_bucket_total{bucket="gt_10"} 2666
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6688
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6201
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 1821850
telemt_user_connections_current{user="hello"} 3055
telemt_user_octets_from_client{user="hello"} 20895831712 (19.46 GB)
telemt_user_octets_to_client{user="hello"} 524189162546 (488.19 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 48405.9 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2879902
telemt_connections_bad_total 640625
telemt_connections_current 3444
telemt_connections_me_current 3444
telemt_handshake_timeouts_total 56412
telemt_upstream_connect_attempt_total 8565
telemt_upstream_connect_success_total 8505
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7275
telemt_me_reconnect_success_total 6070
telemt_me_reader_eof_total 6457
telemt_me_idle_close_by_peer_total 6456
telemt_me_route_drop_no_conn_total 1067487
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1896551
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8313
telemt_desync_full_logged_total 2583
telemt_desync_suppressed_total 5730
telemt_desync_frames_bucket_total{bucket="1_2"} 1595
telemt_desync_frames_bucket_total{bucket="3_10"} 3597
telemt_desync_frames_bucket_total{bucket="gt_10"} 3121
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6199
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6046
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 1895626
telemt_user_connections_current{user="hello"} 3444
telemt_user_octets_from_client{user="hello"} 33195449856 (30.92 GB)
telemt_user_octets_to_client{user="hello"} 768101130716 (715.35 GB)
telemt_user_unique_ips_current{user="hello"} 1221
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 48418.1 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496284
telemt_connections_bad_total 18589
telemt_connections_current 957
telemt_connections_me_current 957
telemt_handshake_timeouts_total 3865
telemt_upstream_connect_attempt_total 12102
telemt_upstream_connect_success_total 11795
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 12102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16943
telemt_me_reconnect_success_total 9355
telemt_me_reader_eof_total 9969
telemt_me_idle_close_by_peer_total 9969
telemt_me_route_drop_no_conn_total 257339
telemt_me_route_drop_channel_closed_total 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 449458
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 950
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 621
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9676
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9324
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 321
telemt_user_connections_total{user="hello"} 449403
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 7285285164 (6.78 GB)
telemt_user_octets_to_client{user="hello"} 167578336404 (156.07 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 48408.4 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2021789
telemt_connections_bad_total 171904
telemt_connections_current 3095
telemt_connections_me_current 3095
telemt_handshake_timeouts_total 72044
telemt_upstream_connect_attempt_total 9742
telemt_upstream_connect_success_total 9741
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8655
telemt_me_reconnect_success_total 7288
telemt_me_reader_eof_total 7712
telemt_me_idle_close_by_peer_total 7711
telemt_me_route_drop_no_conn_total 1035981
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1682380
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9100
telemt_desync_full_logged_total 2932
telemt_desync_suppressed_total 6168
telemt_desync_frames_bucket_total{bucket="1_2"} 1740
telemt_desync_frames_bucket_total{bucket="3_10"} 3463
telemt_desync_frames_bucket_total{bucket="gt_10"} 3897
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7422
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7273
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 1681081
telemt_user_connections_current{user="hello"} 3095
telemt_user_octets_from_client{user="hello"} 22186141988 (20.66 GB)
telemt_user_octets_to_client{user="hello"} 746598330584 (695.32 GB)
telemt_user_unique_ips_current{user="hello"} 987
telemt_user_unique_ips_recent_window{user="hello"} 437
```