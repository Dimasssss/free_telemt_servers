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

# Server Metrics 2026-03-13 09:41:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 94088.6 (26h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369874
telemt_connections_bad_total 3189
telemt_handshake_timeouts_total 7868
telemt_upstream_connect_attempt_total 23747
telemt_upstream_connect_success_total 23636
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 23747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1727
telemt_me_reconnect_attempts_total 22427
telemt_me_reconnect_success_total 18914
telemt_me_reader_eof_total 20212
telemt_me_idle_close_by_peer_total 20211
telemt_me_route_drop_no_conn_total 116098
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317412
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1017
telemt_desync_full_logged_total 378
telemt_desync_suppressed_total 639
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 19222
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18898
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 317103
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 5403530016 (5.03 GB)
telemt_user_octets_to_client{user="hello"} 140452252312 (130.81 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 93981.3 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169442
telemt_connections_bad_total 1543
telemt_handshake_timeouts_total 1301
telemt_upstream_connect_attempt_total 46780
telemt_upstream_connect_success_total 46140
telemt_upstream_connect_fail_total 640
telemt_upstream_connect_attempts_per_request{bucket="1"} 46780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 640
telemt_me_keepalive_timeout_total 728
telemt_me_reconnect_attempts_total 81311
telemt_me_reconnect_success_total 24941
telemt_me_reader_eof_total 27449
telemt_me_idle_close_by_peer_total 27449
telemt_me_route_drop_no_conn_total 71232
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143174
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 26915
telemt_me_refill_failed_total 1759
telemt_me_writer_restored_same_endpoint_total 24926
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1974
telemt_user_connections_total{user="hello"} 159454
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 1671503052 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 52318186715 (48.73 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 93944.8 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206195
telemt_connections_bad_total 2008
telemt_handshake_timeouts_total 4180
telemt_upstream_connect_attempt_total 25410
telemt_upstream_connect_success_total 25407
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 683
telemt_me_reconnect_attempts_total 21850
telemt_me_reconnect_success_total 20660
telemt_me_reader_eof_total 22152
telemt_me_idle_close_by_peer_total 22152
telemt_me_route_drop_no_conn_total 77784
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192431
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 20888
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20640
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 192355
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 8068315780 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 80792310440 (75.24 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 93920.4 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293258
telemt_connections_bad_total 13664
telemt_handshake_timeouts_total 2145
telemt_upstream_connect_attempt_total 38443
telemt_upstream_connect_success_total 28429
telemt_upstream_connect_fail_total 10013
telemt_upstream_connect_attempts_per_request{bucket="1"} 38442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10013
telemt_me_keepalive_timeout_total 3425
telemt_me_reconnect_attempts_total 78783
telemt_me_reconnect_success_total 20866
telemt_me_reader_eof_total 23319
telemt_me_idle_close_by_peer_total 23312
telemt_me_route_drop_no_conn_total 105925
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250861
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 931
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 658
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22941
telemt_me_refill_failed_total 1805
telemt_me_writer_restored_same_endpoint_total 20856
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2075
telemt_user_connections_total{user="hello"} 253584
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 5576133410 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 95484171645 (88.93 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 44092.0 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58076
telemt_connections_bad_total 8865
telemt_handshake_timeouts_total 488
telemt_upstream_connect_attempt_total 15181
telemt_upstream_connect_success_total 15035
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 15181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 373
telemt_me_reconnect_attempts_total 15067
telemt_me_reconnect_success_total 12841
telemt_me_reader_eof_total 13681
telemt_me_idle_close_by_peer_total 13681
telemt_me_route_drop_no_conn_total 17822
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47009
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 13024
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12823
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 47004
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 352709656 (336.37 MB)
telemt_user_octets_to_client{user="hello"} 12783906984 (11.91 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 93877.1 (26h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507890
telemt_connections_bad_total 13925
telemt_handshake_timeouts_total 5713
telemt_upstream_connect_attempt_total 20033
telemt_upstream_connect_success_total 19927
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 20033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1551
telemt_me_reconnect_attempts_total 18897
telemt_me_reconnect_success_total 15246
telemt_me_reader_eof_total 16363
telemt_me_idle_close_by_peer_total 16360
telemt_me_route_drop_no_conn_total 264376
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497199
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 399
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 15556
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15239
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 470288
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 8532824544 (7.95 GB)
telemt_user_octets_to_client{user="hello"} 265021936784 (246.82 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 75
```