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

# Server Metrics 2026-03-16 13:11:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 140194.9 (38h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793833
telemt_connections_bad_total 54231
telemt_handshake_timeouts_total 26119
telemt_upstream_connect_attempt_total 32426
telemt_upstream_connect_success_total 32268
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 32426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 39537
telemt_me_reconnect_success_total 25301
telemt_me_reader_eof_total 27272
telemt_me_idle_close_by_peer_total 27272
telemt_me_route_drop_no_conn_total 618179
telemt_me_route_drop_channel_closed_total 98
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 727227
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3457
telemt_desync_full_logged_total 1305
telemt_desync_suppressed_total 2152
telemt_desync_frames_bucket_total{bucket="1_2"} 732
telemt_desync_frames_bucket_total{bucket="3_10"} 1447
telemt_desync_frames_bucket_total{bucket="gt_10"} 1278
telemt_pool_swap_total 125
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26025
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 25266
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 724
telemt_user_connections_total{user="hello"} 663698
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 13806866172 (12.86 GB)
telemt_user_octets_to_client{user="hello"} 378802604792 (352.79 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 140202.3 (38h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338069
telemt_connections_bad_total 8569
telemt_handshake_timeouts_total 21211
telemt_upstream_connect_attempt_total 37441
telemt_upstream_connect_success_total 37334
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 37441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 891
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 44676
telemt_me_reconnect_success_total 29737
telemt_me_reader_eof_total 31947
telemt_me_idle_close_by_peer_total 31946
telemt_me_route_drop_no_conn_total 157152
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296135
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 247
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 167
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30631
telemt_me_refill_failed_total 457
telemt_me_writer_restored_same_endpoint_total 29721
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 894
telemt_user_connections_total{user="hello"} 295805
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 5850476725 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 142504462124 (132.72 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 140194.8 (38h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319686
telemt_connections_bad_total 8343
telemt_handshake_timeouts_total 9037
telemt_upstream_connect_attempt_total 38623
telemt_upstream_connect_success_total 38615
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 38623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 39021
telemt_me_reconnect_success_total 31572
telemt_me_reader_eof_total 33896
telemt_me_idle_close_by_peer_total 33895
telemt_me_route_drop_no_conn_total 107856
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260654
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 32128
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31564
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 556
telemt_user_connections_total{user="hello"} 260244
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 19212489189 (17.89 GB)
telemt_user_octets_to_client{user="hello"} 133204409224 (124.06 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 140194.4 (38h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491511
telemt_connections_bad_total 5604
telemt_handshake_timeouts_total 6520
telemt_upstream_connect_attempt_total 32557
telemt_upstream_connect_success_total 32507
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 32557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16655
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 31749
telemt_me_reconnect_success_total 25519
telemt_me_reader_eof_total 27329
telemt_me_idle_close_by_peer_total 27328
telemt_me_route_drop_no_conn_total 163439
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448299
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1631
telemt_desync_full_logged_total 540
telemt_desync_suppressed_total 1091
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 702
telemt_desync_frames_bucket_total{bucket="gt_10"} 599
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 26057
telemt_me_refill_failed_total 189
telemt_me_writer_restored_same_endpoint_total 25508
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 448109
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 6773489998 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 168202899648 (156.65 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 115265.8 (32h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302893
telemt_connections_bad_total 55544
telemt_handshake_timeouts_total 6259
telemt_upstream_connect_attempt_total 32699
telemt_upstream_connect_success_total 32519
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 32699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 122226
telemt_me_reconnect_success_total 26605
telemt_me_reader_eof_total 28249
telemt_me_idle_close_by_peer_total 28249
telemt_me_route_drop_no_conn_total 89837
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231875
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 721
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 546
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 26882
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 26501
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 231476
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 3036500637 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 105716073855 (98.46 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 140193.8 (38h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1024294
telemt_connections_bad_total 78280
telemt_handshake_timeouts_total 13087
telemt_upstream_connect_attempt_total 29744
telemt_upstream_connect_success_total 29588
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 29744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 170
telemt_me_reconnect_attempts_total 26233
telemt_me_reconnect_success_total 22581
telemt_me_reader_eof_total 24102
telemt_me_idle_close_by_peer_total 24101
telemt_me_route_drop_no_conn_total 726261
telemt_me_route_drop_channel_closed_total 141
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993209
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 747
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 22969
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 22554
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 851785
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 18132194048 (16.89 GB)
telemt_user_octets_to_client{user="hello"} 487677970560 (454.19 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 92
```