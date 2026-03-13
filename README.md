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

# Server Metrics 2026-03-13 10:02:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 95317.7 (26h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376450
telemt_connections_bad_total 3191
telemt_handshake_timeouts_total 7961
telemt_upstream_connect_attempt_total 24072
telemt_upstream_connect_success_total 23960
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 24072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1743
telemt_me_reconnect_attempts_total 22704
telemt_me_reconnect_success_total 19186
telemt_me_reader_eof_total 20486
telemt_me_idle_close_by_peer_total 20485
telemt_me_route_drop_no_conn_total 117766
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323475
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1046
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 658
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 19496
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19170
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 323179
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 5683788604 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 141685119772 (131.95 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 95210.4 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172632
telemt_connections_bad_total 1560
telemt_handshake_timeouts_total 1313
telemt_upstream_connect_attempt_total 47098
telemt_upstream_connect_success_total 46457
telemt_upstream_connect_fail_total 641
telemt_upstream_connect_attempts_per_request{bucket="1"} 47098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 641
telemt_me_keepalive_timeout_total 733
telemt_me_reconnect_attempts_total 82863
telemt_me_reconnect_success_total 25214
telemt_me_reader_eof_total 27763
telemt_me_idle_close_by_peer_total 27763
telemt_me_route_drop_no_conn_total 73500
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146229
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
telemt_me_writer_removed_unexpected_total 27229
telemt_me_refill_failed_total 1799
telemt_me_writer_restored_same_endpoint_total 25199
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2015
telemt_user_connections_total{user="hello"} 162510
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 1700108024 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 53357830531 (49.69 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 95174.3 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210276
telemt_connections_bad_total 2026
telemt_handshake_timeouts_total 4212
telemt_upstream_connect_attempt_total 25712
telemt_upstream_connect_success_total 25709
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 694
telemt_me_reconnect_attempts_total 22108
telemt_me_reconnect_success_total 20917
telemt_me_reader_eof_total 22428
telemt_me_idle_close_by_peer_total 22428
telemt_me_route_drop_no_conn_total 79096
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196336
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
telemt_me_writer_removed_unexpected_total 21147
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20897
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 196258
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 9159489408 (8.53 GB)
telemt_user_octets_to_client{user="hello"} 81283161524 (75.70 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 95149.6 (26h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297628
telemt_connections_bad_total 13673
telemt_handshake_timeouts_total 2163
telemt_upstream_connect_attempt_total 38658
telemt_upstream_connect_success_total 28641
telemt_upstream_connect_fail_total 10017
telemt_upstream_connect_attempts_per_request{bucket="1"} 38658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10017
telemt_me_keepalive_timeout_total 3426
telemt_me_reconnect_attempts_total 80325
telemt_me_reconnect_success_total 21033
telemt_me_reader_eof_total 23529
telemt_me_idle_close_by_peer_total 23522
telemt_me_route_drop_no_conn_total 107625
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255066
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 958
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 676
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23151
telemt_me_refill_failed_total 1848
telemt_me_writer_restored_same_endpoint_total 21023
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2118
telemt_user_connections_total{user="hello"} 257790
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 5616104810 (5.23 GB)
telemt_user_octets_to_client{user="hello"} 96540860161 (89.91 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 45321.2 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60299
telemt_connections_bad_total 9087
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 15616
telemt_upstream_connect_success_total 15465
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 15616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 381
telemt_me_reconnect_attempts_total 15410
telemt_me_reconnect_success_total 13182
telemt_me_reader_eof_total 14042
telemt_me_idle_close_by_peer_total 14042
telemt_me_route_drop_no_conn_total 18570
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48914
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
telemt_me_writer_removed_unexpected_total 13369
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 13164
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 48909
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 377502472 (360.01 MB)
telemt_user_octets_to_client{user="hello"} 13305548588 (12.39 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 95106.3 (26h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518658
telemt_connections_bad_total 14497
telemt_handshake_timeouts_total 6710
telemt_upstream_connect_attempt_total 20261
telemt_upstream_connect_success_total 20155
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 20261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1551
telemt_me_reconnect_attempts_total 19080
telemt_me_reconnect_success_total 15427
telemt_me_reader_eof_total 16549
telemt_me_idle_close_by_peer_total 16546
telemt_me_route_drop_no_conn_total 267786
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506080
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 408
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 250
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 15742
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15420
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 479160
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 8604756692 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 270039987600 (251.49 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 74
```