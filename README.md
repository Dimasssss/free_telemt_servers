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

# Server Metrics 2026-03-13 06:16:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 81796.2 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309560
telemt_connections_bad_total 3086
telemt_handshake_timeouts_total 6356
telemt_upstream_connect_attempt_total 20625
telemt_upstream_connect_success_total 20528
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 20625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1614
telemt_me_reconnect_attempts_total 19933
telemt_me_reconnect_success_total 16433
telemt_me_reader_eof_total 17564
telemt_me_idle_close_by_peer_total 17563
telemt_me_route_drop_no_conn_total 96411
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261544
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 909
telemt_desync_full_logged_total 338
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 397
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 16719
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16417
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 261476
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 4456064704 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 125308598320 (116.70 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 81689.0 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141983
telemt_connections_bad_total 1416
telemt_handshake_timeouts_total 1061
telemt_upstream_connect_attempt_total 42897
telemt_upstream_connect_success_total 42340
telemt_upstream_connect_fail_total 557
telemt_upstream_connect_attempts_per_request{bucket="1"} 42897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 557
telemt_me_keepalive_timeout_total 622
telemt_me_reconnect_attempts_total 70954
telemt_me_reconnect_success_total 21764
telemt_me_reader_eof_total 23954
telemt_me_idle_close_by_peer_total 23954
telemt_me_route_drop_no_conn_total 53472
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117847
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 23469
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 21749
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1705
telemt_user_connections_total{user="hello"} 134344
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 1392737400 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 41617327611 (38.76 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 81653.4 (22h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171740
telemt_connections_bad_total 1910
telemt_handshake_timeouts_total 2794
telemt_upstream_connect_attempt_total 22413
telemt_upstream_connect_success_total 22411
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 497
telemt_me_reconnect_attempts_total 19467
telemt_me_reconnect_success_total 18296
telemt_me_reader_eof_total 19612
telemt_me_idle_close_by_peer_total 19612
telemt_me_route_drop_no_conn_total 66473
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160638
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
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 18495
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18276
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 160566
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 2947604136 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 72698661772 (67.71 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 81628.2 (22h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247942
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1832
telemt_upstream_connect_attempt_total 34785
telemt_upstream_connect_success_total 24865
telemt_upstream_connect_fail_total 9920
telemt_upstream_connect_attempts_per_request{bucket="1"} 34785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9920
telemt_me_keepalive_timeout_total 3345
telemt_me_reconnect_attempts_total 69467
telemt_me_reconnect_success_total 17932
telemt_me_reader_eof_total 20080
telemt_me_idle_close_by_peer_total 20073
telemt_me_route_drop_no_conn_total 90073
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208686
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 626
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 19773
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17922
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1841
telemt_user_connections_total{user="hello"} 211426
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 3327425754 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 82146202093 (76.50 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 31799.7 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35877
telemt_connections_bad_total 6627
telemt_handshake_timeouts_total 154
telemt_upstream_connect_attempt_total 11071
telemt_upstream_connect_success_total 10965
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 11071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 264
telemt_me_reconnect_attempts_total 10316
telemt_me_reconnect_success_total 9352
telemt_me_reader_eof_total 9973
telemt_me_idle_close_by_peer_total 9973
telemt_me_route_drop_no_conn_total 9855
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28163
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 9465
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9334
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 28163
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 212935212 (203.07 MB)
telemt_user_octets_to_client{user="hello"} 9924569728 (9.24 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 81584.6 (22h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418075
telemt_connections_bad_total 8034
telemt_handshake_timeouts_total 3186
telemt_upstream_connect_attempt_total 17411
telemt_upstream_connect_success_total 17315
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 1454
telemt_me_reconnect_attempts_total 16895
telemt_me_reconnect_success_total 13262
telemt_me_reader_eof_total 14243
telemt_me_idle_close_by_peer_total 14240
telemt_me_route_drop_no_conn_total 185825
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405538
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 13541
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13255
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 393774
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 6442797096 (6.00 GB)
telemt_user_octets_to_client{user="hello"} 231537919884 (215.64 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 64
```