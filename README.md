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

# Server Metrics 2026-03-13 07:33:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 86406.3 (24h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331979
telemt_connections_bad_total 3167
telemt_handshake_timeouts_total 7472
telemt_upstream_connect_attempt_total 21681
telemt_upstream_connect_success_total 21582
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 21681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1651
telemt_me_reconnect_attempts_total 20770
telemt_me_reconnect_success_total 17265
telemt_me_reader_eof_total 18461
telemt_me_idle_close_by_peer_total 18460
telemt_me_route_drop_no_conn_total 103864
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282029
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 944
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 17559
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17249
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 281727
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 4709431124 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 131697511108 (122.65 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 86299.0 (23h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151010
telemt_connections_bad_total 1477
telemt_handshake_timeouts_total 1164
telemt_upstream_connect_attempt_total 44503
telemt_upstream_connect_success_total 43909
telemt_upstream_connect_fail_total 594
telemt_upstream_connect_attempts_per_request{bucket="1"} 44503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 511
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 594
telemt_me_keepalive_timeout_total 667
telemt_me_reconnect_attempts_total 74676
telemt_me_reconnect_success_total 23114
telemt_me_reader_eof_total 25412
telemt_me_idle_close_by_peer_total 25412
telemt_me_route_drop_no_conn_total 56927
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126377
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 18
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 24911
telemt_me_refill_failed_total 1609
telemt_me_writer_restored_same_endpoint_total 23099
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1797
telemt_user_connections_total{user="hello"} 142869
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 1483508544 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 45952739087 (42.80 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 86262.8 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183193
telemt_connections_bad_total 1971
telemt_handshake_timeouts_total 3073
telemt_upstream_connect_attempt_total 23452
telemt_upstream_connect_success_total 23450
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 562
telemt_me_reconnect_attempts_total 20289
telemt_me_reconnect_success_total 19113
telemt_me_reader_eof_total 20492
telemt_me_idle_close_by_peer_total 20492
telemt_me_route_drop_no_conn_total 70664
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171347
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19321
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19093
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 171276
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 3022246552 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 74289902684 (69.19 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 86238.3 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263443
telemt_connections_bad_total 13616
telemt_handshake_timeouts_total 2000
telemt_upstream_connect_attempt_total 36095
telemt_upstream_connect_success_total 26149
telemt_upstream_connect_fail_total 9946
telemt_upstream_connect_attempts_per_request{bucket="1"} 36095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12869
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9946
telemt_me_keepalive_timeout_total 3363
telemt_me_reconnect_attempts_total 70534
telemt_me_reconnect_success_total 18994
telemt_me_reader_eof_total 21212
telemt_me_idle_close_by_peer_total 21205
telemt_me_route_drop_no_conn_total 95087
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222909
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 749
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 20850
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18984
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1856
telemt_user_connections_total{user="hello"} 225638
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 5208686142 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 86282327701 (80.36 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 36409.9 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44505
telemt_connections_bad_total 7479
telemt_handshake_timeouts_total 401
telemt_upstream_connect_attempt_total 12368
telemt_upstream_connect_success_total 12241
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 12368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 295
telemt_me_reconnect_attempts_total 11377
telemt_me_reconnect_success_total 10408
telemt_me_reader_eof_total 11096
telemt_me_idle_close_by_peer_total 11096
telemt_me_route_drop_no_conn_total 12758
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35412
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 35
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 10532
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10390
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 35411
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 259513676 (247.49 MB)
telemt_user_octets_to_client{user="hello"} 10948716484 (10.20 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 86194.8 (23h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449388
telemt_connections_bad_total 11096
telemt_handshake_timeouts_total 3522
telemt_upstream_connect_attempt_total 18302
telemt_upstream_connect_success_total 18204
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 18302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 1503
telemt_me_reconnect_attempts_total 17568
telemt_me_reconnect_success_total 13928
telemt_me_reader_eof_total 14959
telemt_me_idle_close_by_peer_total 14956
telemt_me_route_drop_no_conn_total 205158
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433996
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 363
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14218
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13921
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 419336
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 7807872808 (7.27 GB)
telemt_user_octets_to_client{user="hello"} 243101949412 (226.41 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 63
```