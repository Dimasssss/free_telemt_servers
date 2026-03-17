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

# Server Metrics 2026-03-17 15:10:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 73488.5 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 801556
telemt_connections_bad_total 6041
telemt_handshake_timeouts_total 23390
telemt_upstream_connect_attempt_total 17578
telemt_upstream_connect_success_total 17118
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 17578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 25835
telemt_me_reconnect_success_total 11133
telemt_me_reader_eof_total 12141
telemt_me_idle_close_by_peer_total 12140
telemt_me_route_drop_no_conn_total 333230
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 727943
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5112
telemt_desync_full_logged_total 1411
telemt_desync_suppressed_total 3701
telemt_desync_frames_bucket_total{bucket="1_2"} 1487
telemt_desync_frames_bucket_total{bucket="3_10"} 2029
telemt_desync_frames_bucket_total{bucket="gt_10"} 1596
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11745
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11111
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 729791
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 11859695543 (11.05 GB)
telemt_user_octets_to_client{user="hello"} 242854089199 (226.18 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 73739.5 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517390
telemt_connections_bad_total 31795
telemt_handshake_timeouts_total 26190
telemt_upstream_connect_attempt_total 86280
telemt_upstream_connect_success_total 85771
telemt_upstream_connect_fail_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 86278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12260
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 507
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 37320
telemt_me_reconnect_success_total 13438
telemt_me_reader_eof_total 14740
telemt_me_idle_close_by_peer_total 14740
telemt_me_route_drop_no_conn_total 191948
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366653
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1473
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 1009
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14347
telemt_me_refill_failed_total 742
telemt_me_writer_restored_same_endpoint_total 13422
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 909
telemt_user_connections_total{user="hello"} 435199
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 4823165972 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 128093294854 (119.30 GB)
telemt_user_msgs_from_client{user="hello"} 994919
telemt_user_msgs_to_client{user="hello"} 3429759
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 73515.7 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268349
telemt_connections_bad_total 7834
telemt_handshake_timeouts_total 17707
telemt_upstream_connect_attempt_total 19279
telemt_upstream_connect_success_total 19180
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 19279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 27860
telemt_me_reconnect_success_total 15446
telemt_me_reader_eof_total 16699
telemt_me_idle_close_by_peer_total 16696
telemt_me_route_drop_no_conn_total 126050
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228883
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16043
telemt_me_refill_failed_total 385
telemt_me_writer_restored_same_endpoint_total 15435
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 228744
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 18306309644 (17.05 GB)
telemt_user_octets_to_client{user="hello"} 56550588900 (52.67 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 73575.1 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618594
telemt_connections_bad_total 8570
telemt_handshake_timeouts_total 13573
telemt_upstream_connect_attempt_total 16823
telemt_upstream_connect_success_total 16665
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 16823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 26744
telemt_me_reconnect_success_total 11929
telemt_me_reader_eof_total 13042
telemt_me_idle_close_by_peer_total 13041
telemt_me_route_drop_no_conn_total 245122
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531691
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1841
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 1217
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 822
telemt_desync_frames_bucket_total{bucket="gt_10"} 554
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12599
telemt_me_refill_failed_total 458
telemt_me_writer_restored_same_endpoint_total 11920
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 670
telemt_user_connections_total{user="hello"} 532514
telemt_user_connections_current{user="hello"} 740
telemt_user_octets_from_client{user="hello"} 6527445966 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 166992573627 (155.52 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 73547.1 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290113
telemt_connections_bad_total 57329
telemt_handshake_timeouts_total 3644
telemt_upstream_connect_attempt_total 21286
telemt_upstream_connect_success_total 20815
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 21286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 41194
telemt_me_reconnect_success_total 16722
telemt_me_reader_eof_total 18077
telemt_me_idle_close_by_peer_total 18075
telemt_me_route_drop_no_conn_total 82073
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216931
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17766
telemt_me_refill_failed_total 760
telemt_me_writer_restored_same_endpoint_total 16714
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1044
telemt_user_connections_total{user="hello"} 217435
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 2726902059 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 79924658447 (74.44 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 73708.9 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702071
telemt_connections_bad_total 56097
telemt_handshake_timeouts_total 6973
telemt_upstream_connect_attempt_total 14835
telemt_upstream_connect_success_total 14753
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 14835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 21353
telemt_me_reconnect_success_total 11058
telemt_me_reader_eof_total 12033
telemt_me_idle_close_by_peer_total 12033
telemt_me_route_drop_no_conn_total 508493
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711273
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1000
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 403
telemt_desync_frames_bucket_total{bucket="gt_10"} 347
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11554
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11044
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 603285
telemt_user_connections_current{user="hello"} 993
telemt_user_octets_from_client{user="hello"} 8873990044 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 269404325640 (250.90 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 21475.1 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16815
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 11671
telemt_upstream_connect_success_total 11573
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 11671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 21883
telemt_me_reconnect_success_total 10323
telemt_me_reader_eof_total 10921
telemt_me_idle_close_by_peer_total 10921
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 6240
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16015
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 10789
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 10308
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 16113
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 491561901 (468.79 MB)
telemt_user_octets_to_client{user="hello"} 23516034842 (21.90 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```