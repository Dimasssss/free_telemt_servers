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

# Server Metrics 2026-03-13 06:01:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 80874.4 (22h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306437
telemt_connections_bad_total 3083
telemt_handshake_timeouts_total 6279
telemt_upstream_connect_attempt_total 20377
telemt_upstream_connect_success_total 20280
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 20377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1590
telemt_me_reconnect_attempts_total 19728
telemt_me_reconnect_success_total 16227
telemt_me_reader_eof_total 17341
telemt_me_idle_close_by_peer_total 17340
telemt_me_route_drop_no_conn_total 95550
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258647
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 896
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 563
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 392
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16514
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16211
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 258583
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 4412396616 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 124702235248 (116.14 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 80767.2 (22h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139879
telemt_connections_bad_total 780
telemt_handshake_timeouts_total 1047
telemt_upstream_connect_attempt_total 42623
telemt_upstream_connect_success_total 42077
telemt_upstream_connect_fail_total 546
telemt_upstream_connect_attempts_per_request{bucket="1"} 42623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 546
telemt_me_keepalive_timeout_total 595
telemt_me_reconnect_attempts_total 69423
telemt_me_reconnect_success_total 21546
telemt_me_reader_eof_total 23694
telemt_me_idle_close_by_peer_total 23694
telemt_me_route_drop_no_conn_total 52802
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116438
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_me_writer_removed_unexpected_total 23209
telemt_me_refill_failed_total 1494
telemt_me_writer_restored_same_endpoint_total 21531
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1663
telemt_user_connections_total{user="hello"} 132935
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 1383296604 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 40509307631 (37.73 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 80730.6 (22h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169758
telemt_connections_bad_total 1908
telemt_handshake_timeouts_total 2759
telemt_upstream_connect_attempt_total 22197
telemt_upstream_connect_success_total 22195
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 467
telemt_me_reconnect_attempts_total 19294
telemt_me_reconnect_success_total 18125
telemt_me_reader_eof_total 19426
telemt_me_idle_close_by_peer_total 19426
telemt_me_route_drop_no_conn_total 65651
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158777
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
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18322
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18105
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 158705
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 2933770304 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 72327121236 (67.36 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 80706.5 (22h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244876
telemt_connections_bad_total 13609
telemt_handshake_timeouts_total 1822
telemt_upstream_connect_attempt_total 34434
telemt_upstream_connect_success_total 24521
telemt_upstream_connect_fail_total 9913
telemt_upstream_connect_attempts_per_request{bucket="1"} 34434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9913
telemt_me_keepalive_timeout_total 3319
telemt_me_reconnect_attempts_total 69166
telemt_me_reconnect_success_total 17633
telemt_me_reader_eof_total 19776
telemt_me_idle_close_by_peer_total 19769
telemt_me_route_drop_no_conn_total 89214
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205762
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 579
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 411
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 19469
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17623
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1836
telemt_user_connections_total{user="hello"} 208504
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 3317087786 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 81848711989 (76.23 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 30878.1 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33676
telemt_connections_bad_total 6004
telemt_handshake_timeouts_total 139
telemt_upstream_connect_attempt_total 10536
telemt_upstream_connect_success_total 10433
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 10536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 9827
telemt_me_reconnect_success_total 8865
telemt_me_reader_eof_total 9436
telemt_me_idle_close_by_peer_total 9436
telemt_me_route_drop_no_conn_total 9393
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26650
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 8977
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 8847
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 26650
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 206210828 (196.66 MB)
telemt_user_octets_to_client{user="hello"} 9609559092 (8.95 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 80662.9 (22h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413336
telemt_connections_bad_total 8032
telemt_handshake_timeouts_total 3123
telemt_upstream_connect_attempt_total 17212
telemt_upstream_connect_success_total 17118
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 17212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1452
telemt_me_reconnect_attempts_total 16741
telemt_me_reconnect_success_total 13109
telemt_me_reader_eof_total 14077
telemt_me_idle_close_by_peer_total 14074
telemt_me_route_drop_no_conn_total 183602
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400962
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 346
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 13387
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13102
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 389207
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 6397408580 (5.96 GB)
telemt_user_octets_to_client{user="hello"} 230417142756 (214.59 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 51
```