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

# Server Metrics 2026-03-17 06:19:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 41646.3 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243203
telemt_connections_bad_total 3352
telemt_handshake_timeouts_total 8005
telemt_upstream_connect_attempt_total 8720
telemt_upstream_connect_success_total 8674
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6613
telemt_me_reconnect_success_total 6589
telemt_me_reader_eof_total 7015
telemt_me_idle_close_by_peer_total 7015
telemt_me_route_drop_no_conn_total 75468
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219993
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1585
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 1082
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 817
telemt_desync_frames_bucket_total{bucket="gt_10"} 408
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6655
telemt_me_writer_restored_same_endpoint_total 6568
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 219783
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 2964780364 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 96501212760 (89.87 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 41897.9 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138576
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 10569
telemt_upstream_connect_attempt_total 11490
telemt_upstream_connect_success_total 11343
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 11490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 10444
telemt_me_reconnect_success_total 9268
telemt_me_reader_eof_total 9811
telemt_me_idle_close_by_peer_total 9811
telemt_me_route_drop_no_conn_total 52168
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120749
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 321
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9389
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9252
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 120758
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 1485127092 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 51466174316 (47.93 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 41674.0 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82641
telemt_connections_bad_total 1110
telemt_handshake_timeouts_total 2667
telemt_upstream_connect_attempt_total 11230
telemt_upstream_connect_success_total 11171
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 11230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9115
telemt_me_reconnect_success_total 9066
telemt_me_reader_eof_total 9708
telemt_me_idle_close_by_peer_total 9708
telemt_me_route_drop_no_conn_total 28224
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71268
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9175
telemt_me_writer_restored_same_endpoint_total 9055
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 71251
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 6100222876 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 23156272712 (21.57 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 41733.4 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145518
telemt_connections_bad_total 3787
telemt_handshake_timeouts_total 5958
telemt_upstream_connect_attempt_total 9451
telemt_upstream_connect_success_total 9370
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 9451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_reconnect_attempts_total 7284
telemt_me_reconnect_success_total 7229
telemt_me_reader_eof_total 7698
telemt_me_idle_close_by_peer_total 7698
telemt_me_route_drop_no_conn_total 48359
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131504
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7333
telemt_me_writer_restored_same_endpoint_total 7222
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 131521
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 1407185794 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 63418330521 (59.06 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 41705.2 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110608
telemt_connections_bad_total 32408
telemt_handshake_timeouts_total 2059
telemt_upstream_connect_attempt_total 12541
telemt_upstream_connect_success_total 12372
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 12541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_reconnect_attempts_total 12434
telemt_me_reconnect_success_total 10168
telemt_me_reader_eof_total 10725
telemt_me_idle_close_by_peer_total 10725
telemt_me_route_drop_no_conn_total 28255
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73204
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10371
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 10160
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 73301
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 777563163 (741.54 MB)
telemt_user_octets_to_client{user="hello"} 31830238010 (29.64 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 41866.8 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266876
telemt_connections_bad_total 37181
telemt_handshake_timeouts_total 2141
telemt_upstream_connect_attempt_total 8579
telemt_upstream_connect_success_total 8534
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6479
telemt_me_reconnect_success_total 6450
telemt_me_reader_eof_total 6915
telemt_me_idle_close_by_peer_total 6915
telemt_me_route_drop_no_conn_total 219454
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295729
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 250
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6545
telemt_me_writer_restored_same_endpoint_total 6440
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 217671
telemt_user_connections_current{user="hello"} 724
telemt_user_octets_from_client{user="hello"} 3274153220 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 152939391540 (142.44 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 29872.8 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 889
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 14730
telemt_upstream_connect_success_total 14730
telemt_upstream_connect_attempts_per_request{bucket="1"} 14730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 13230
telemt_me_reconnect_success_total 13156
telemt_me_reader_eof_total 14427
telemt_me_idle_close_by_peer_total 14427
telemt_me_route_drop_no_conn_total 101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 690
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 13277
telemt_me_writer_restored_same_endpoint_total 13156
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 690
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 194713604 (185.69 MB)
telemt_user_octets_to_client{user="hello"} 11117986932 (10.35 GB)
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```