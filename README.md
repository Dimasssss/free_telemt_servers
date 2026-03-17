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

# Server Metrics 2026-03-17 07:51:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 47142.1 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317098
telemt_connections_bad_total 3549
telemt_handshake_timeouts_total 9817
telemt_upstream_connect_attempt_total 9708
telemt_upstream_connect_success_total 9655
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 9708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7331
telemt_me_reconnect_success_total 7302
telemt_me_reader_eof_total 7769
telemt_me_idle_close_by_peer_total 7769
telemt_me_route_drop_no_conn_total 97261
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285625
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2208
telemt_desync_full_logged_total 637
telemt_desync_suppressed_total 1571
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 1087
telemt_desync_frames_bucket_total{bucket="gt_10"} 632
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7378
telemt_me_writer_restored_same_endpoint_total 7281
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 285390
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 3906613128 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 122875005592 (114.44 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 47393.2 (13h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178556
telemt_connections_bad_total 2350
telemt_handshake_timeouts_total 11904
telemt_upstream_connect_attempt_total 12975
telemt_upstream_connect_success_total 12807
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 12975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_reconnect_attempts_total 12734
telemt_me_reconnect_success_total 10461
telemt_me_reader_eof_total 11069
telemt_me_idle_close_by_peer_total 11069
telemt_me_route_drop_no_conn_total 64120
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155042
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 393
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 250
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10630
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10445
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 155070
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 1877428248 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 62439584188 (58.15 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 47169.7 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108793
telemt_connections_bad_total 5138
telemt_handshake_timeouts_total 5005
telemt_upstream_connect_attempt_total 12351
telemt_upstream_connect_success_total 12287
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9969
telemt_me_reconnect_success_total 9909
telemt_me_reader_eof_total 10615
telemt_me_idle_close_by_peer_total 10615
telemt_me_route_drop_no_conn_total 34119
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89905
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 159
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10034
telemt_me_writer_restored_same_endpoint_total 9898
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 89861
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 6485809108 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 27861157384 (25.95 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 47228.6 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210521
telemt_connections_bad_total 6057
telemt_handshake_timeouts_total 10084
telemt_upstream_connect_attempt_total 10861
telemt_upstream_connect_success_total 10769
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 10861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9413
telemt_me_reconnect_success_total 8351
telemt_me_reader_eof_total 8885
telemt_me_idle_close_by_peer_total 8885
telemt_me_route_drop_no_conn_total 63021
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177969
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 367
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 239
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8505
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8343
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 177974
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 1873326690 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 79448886001 (73.99 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 47200.6 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136395
telemt_connections_bad_total 38821
telemt_handshake_timeouts_total 2463
telemt_upstream_connect_attempt_total 14456
telemt_upstream_connect_success_total 14267
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 14456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 15056
telemt_me_reconnect_success_total 11792
telemt_me_reader_eof_total 12439
telemt_me_idle_close_by_peer_total 12439
telemt_me_route_drop_no_conn_total 35677
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91071
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 141
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12042
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11784
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 91110
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 950555231 (906.52 MB)
telemt_user_octets_to_client{user="hello"} 43075225554 (40.12 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 47361.7 (13h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323000
telemt_connections_bad_total 42169
telemt_handshake_timeouts_total 2939
telemt_upstream_connect_attempt_total 9822
telemt_upstream_connect_success_total 9771
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 10008
telemt_me_reconnect_success_total 7413
telemt_me_reader_eof_total 7978
telemt_me_idle_close_by_peer_total 7978
telemt_me_route_drop_no_conn_total 241611
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343261
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 358
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7599
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 7399
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 265188
telemt_user_connections_current{user="hello"} 765
telemt_user_octets_from_client{user="hello"} 3731005432 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 165480905316 (154.12 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 35368.1 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1739
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 17589
telemt_upstream_connect_success_total 17588
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15828
telemt_me_reconnect_success_total 15737
telemt_me_reader_eof_total 17230
telemt_me_idle_close_by_peer_total 17230
telemt_me_route_drop_no_conn_total 262
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1527
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15876
telemt_me_writer_restored_same_endpoint_total 15737
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1527
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 224690176 (214.28 MB)
telemt_user_octets_to_client{user="hello"} 16829688672 (15.67 GB)
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```