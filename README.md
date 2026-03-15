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

# Server Metrics 2026-03-15 17:11:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 68200.0 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315933
telemt_connections_bad_total 2800
telemt_handshake_timeouts_total 9221
telemt_upstream_connect_attempt_total 16676
telemt_upstream_connect_success_total 16589
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16580
telemt_me_reconnect_success_total 13188
telemt_me_reader_eof_total 14046
telemt_me_idle_close_by_peer_total 14046
telemt_me_route_drop_no_conn_total 457074
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 352477
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1806
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 760
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13434
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13154
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 291577
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 6023697896 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 235012177572 (218.87 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 68206.6 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124353
telemt_connections_bad_total 2825
telemt_handshake_timeouts_total 11507
telemt_upstream_connect_attempt_total 18703
telemt_upstream_connect_success_total 18703
telemt_upstream_connect_attempts_per_request{bucket="1"} 18703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 17621
telemt_me_reconnect_success_total 15257
telemt_me_reader_eof_total 16305
telemt_me_idle_close_by_peer_total 16304
telemt_me_route_drop_no_conn_total 52267
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106375
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15522
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15241
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 106358
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 2063468728 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 53197814436 (49.54 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 68198.9 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129811
telemt_connections_bad_total 1679
telemt_handshake_timeouts_total 3141
telemt_upstream_connect_attempt_total 20214
telemt_upstream_connect_success_total 20206
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24103
telemt_me_reconnect_success_total 16747
telemt_me_reader_eof_total 17969
telemt_me_idle_close_by_peer_total 17969
telemt_me_route_drop_no_conn_total 50782
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113690
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 17136
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16739
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 113584
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 10558711828 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 64172132400 (59.76 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 68198.5 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175414
telemt_connections_bad_total 919
telemt_handshake_timeouts_total 1081
telemt_upstream_connect_attempt_total 16311
telemt_upstream_connect_success_total 16299
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12977
telemt_me_reconnect_success_total 12896
telemt_me_reader_eof_total 13721
telemt_me_idle_close_by_peer_total 13721
telemt_me_route_drop_no_conn_total 68096
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161687
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 557
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 357
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13053
telemt_me_writer_restored_same_endpoint_total 12885
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 161600
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 3052390460 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 73100238848 (68.08 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 43269.9 (12h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107166
telemt_connections_bad_total 23192
telemt_handshake_timeouts_total 2374
telemt_upstream_connect_attempt_total 13202
telemt_upstream_connect_success_total 13126
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105212
telemt_me_reconnect_success_total 10770
telemt_me_reader_eof_total 11295
telemt_me_idle_close_by_peer_total 11295
telemt_me_route_drop_no_conn_total 36596
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78811
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 10828
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10666
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 78944
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 1332851961 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 31291839095 (29.14 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 68198.3 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451168
telemt_connections_bad_total 57532
telemt_handshake_timeouts_total 3715
telemt_upstream_connect_attempt_total 14807
telemt_upstream_connect_success_total 14719
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 14807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 12590
telemt_me_reconnect_success_total 11288
telemt_me_reader_eof_total 11993
telemt_me_idle_close_by_peer_total 11993
telemt_me_route_drop_no_conn_total 273296
telemt_me_route_drop_channel_closed_total 69
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404689
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11448
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11261
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 373396
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 10006638184 (9.32 GB)
telemt_user_octets_to_client{user="hello"} 198656434744 (185.01 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 72
```