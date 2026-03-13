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

# Server Metrics 2026-03-13 10:12:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 95932.2 (26h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379797
telemt_connections_bad_total 3192
telemt_handshake_timeouts_total 8055
telemt_upstream_connect_attempt_total 24251
telemt_upstream_connect_success_total 24139
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 24251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1751
telemt_me_reconnect_attempts_total 22840
telemt_me_reconnect_success_total 19321
telemt_me_reader_eof_total 20640
telemt_me_idle_close_by_peer_total 20639
telemt_me_route_drop_no_conn_total 118825
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326652
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1061
telemt_desync_full_logged_total 394
telemt_desync_suppressed_total 667
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 454
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 19632
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19305
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 326356
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 5747834276 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 142536533648 (132.75 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 95824.7 (26h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174233
telemt_connections_bad_total 1563
telemt_handshake_timeouts_total 1321
telemt_upstream_connect_attempt_total 47270
telemt_upstream_connect_success_total 46620
telemt_upstream_connect_fail_total 650
telemt_upstream_connect_attempts_per_request{bucket="1"} 47270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 650
telemt_me_keepalive_timeout_total 735
telemt_me_reconnect_attempts_total 84319
telemt_me_reconnect_success_total 25332
telemt_me_reader_eof_total 27924
telemt_me_idle_close_by_peer_total 27924
telemt_me_route_drop_no_conn_total 74274
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147724
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 20
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
telemt_me_writer_removed_unexpected_total 27390
telemt_me_refill_failed_total 1840
telemt_me_writer_restored_same_endpoint_total 25316
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2058
telemt_user_connections_total{user="hello"} 164004
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 1707043332 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 53638411491 (49.95 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 95788.4 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212272
telemt_connections_bad_total 2036
telemt_handshake_timeouts_total 4262
telemt_upstream_connect_attempt_total 25915
telemt_upstream_connect_success_total 25912
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 740
telemt_me_reconnect_attempts_total 22265
telemt_me_reconnect_success_total 21067
telemt_me_reader_eof_total 22581
telemt_me_idle_close_by_peer_total 22581
telemt_me_route_drop_no_conn_total 79698
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198223
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
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 21300
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21047
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 198144
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 9170995220 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 81550957464 (75.95 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 95764.1 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300442
telemt_connections_bad_total 13675
telemt_handshake_timeouts_total 2178
telemt_upstream_connect_attempt_total 38780
telemt_upstream_connect_success_total 28759
telemt_upstream_connect_fail_total 10021
telemt_upstream_connect_attempts_per_request{bucket="1"} 38780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14146
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10021
telemt_me_keepalive_timeout_total 3433
telemt_me_reconnect_attempts_total 81677
telemt_me_reconnect_success_total 21105
telemt_me_reader_eof_total 23643
telemt_me_idle_close_by_peer_total 23636
telemt_me_route_drop_no_conn_total 108532
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257685
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 966
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23265
telemt_me_refill_failed_total 1888
telemt_me_writer_restored_same_endpoint_total 21095
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2160
telemt_user_connections_total{user="hello"} 260406
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 5639833238 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 97271793509 (90.59 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 45935.5 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61600
telemt_connections_bad_total 9197
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 15826
telemt_upstream_connect_success_total 15675
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 15826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 15614
telemt_me_reconnect_success_total 13385
telemt_me_reader_eof_total 14246
telemt_me_idle_close_by_peer_total 14246
telemt_me_route_drop_no_conn_total 19095
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50068
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 13573
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 13367
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 50063
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 461602660 (440.22 MB)
telemt_user_octets_to_client{user="hello"} 13487040656 (12.56 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 95720.6 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523178
telemt_connections_bad_total 14505
telemt_handshake_timeouts_total 7281
telemt_upstream_connect_attempt_total 20456
telemt_upstream_connect_success_total 20349
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 20456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1581
telemt_me_reconnect_attempts_total 19229
telemt_me_reconnect_success_total 15574
telemt_me_reader_eof_total 16701
telemt_me_idle_close_by_peer_total 16698
telemt_me_route_drop_no_conn_total 269339
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509856
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 414
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 15894
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15567
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 482951
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 8633998252 (8.04 GB)
telemt_user_octets_to_client{user="hello"} 271945485940 (253.27 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 61
```