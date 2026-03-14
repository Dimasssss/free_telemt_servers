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

# Server Metrics 2026-03-14 21:04:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 28061.1 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139629
telemt_connections_bad_total 16251
telemt_handshake_timeouts_total 1494
telemt_upstream_connect_attempt_total 6311
telemt_upstream_connect_success_total 6309
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 4890
telemt_me_reconnect_success_total 4853
telemt_me_reader_eof_total 5145
telemt_me_idle_close_by_peer_total 5145
telemt_me_route_drop_no_conn_total 50676
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115598
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 548
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4934
telemt_me_writer_restored_same_endpoint_total 4835
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 115518
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 2470689728 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 69327718816 (64.57 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 28059.2 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57744
telemt_connections_bad_total 731
telemt_handshake_timeouts_total 991
telemt_upstream_connect_attempt_total 7326
telemt_upstream_connect_success_total 7279
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 7326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 8401
telemt_me_reconnect_success_total 5821
telemt_me_reader_eof_total 6189
telemt_me_idle_close_by_peer_total 6189
telemt_me_route_drop_no_conn_total 31122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53838
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5979
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5816
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 53760
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 1367187060 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 24339598328 (22.67 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 28063.7 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64566
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 1893
telemt_upstream_connect_attempt_total 9172
telemt_upstream_connect_success_total 9076
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 9172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 254
telemt_me_reconnect_attempts_total 105166
telemt_me_reconnect_success_total 7302
telemt_me_reader_eof_total 7804
telemt_me_idle_close_by_peer_total 7804
telemt_me_route_drop_no_conn_total 24365
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58961
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7582
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 7256
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 59027
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 3875651405 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 42614408422 (39.69 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 28068.4 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82417
telemt_connections_bad_total 206
telemt_handshake_timeouts_total 607
telemt_upstream_connect_attempt_total 6910
telemt_upstream_connect_success_total 6867
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 6910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 193
telemt_me_reconnect_attempts_total 5274
telemt_me_reconnect_success_total 5247
telemt_me_reader_eof_total 5525
telemt_me_idle_close_by_peer_total 5525
telemt_me_route_drop_no_conn_total 35558
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78094
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 630
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5305
telemt_me_writer_restored_same_endpoint_total 5245
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 78140
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1286704752 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 27341930942 (25.46 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 28061.5 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60493
telemt_connections_bad_total 5429
telemt_handshake_timeouts_total 3336
telemt_upstream_connect_attempt_total 6820
telemt_upstream_connect_success_total 6741
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 6820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 201
telemt_me_reconnect_attempts_total 11817
telemt_me_reconnect_success_total 5279
telemt_me_reader_eof_total 5715
telemt_me_idle_close_by_peer_total 5715
telemt_me_route_drop_no_conn_total 19860
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48851
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5533
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 5275
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 48838
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 1384668808 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 30092448388 (28.03 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 28061.1 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207445
telemt_connections_bad_total 7312
telemt_handshake_timeouts_total 2663
telemt_upstream_connect_attempt_total 5520
telemt_upstream_connect_success_total 5415
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 5520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 253
telemt_me_reconnect_attempts_total 8966
telemt_me_reconnect_success_total 3957
telemt_me_reader_eof_total 4288
telemt_me_idle_close_by_peer_total 4288
telemt_me_route_drop_no_conn_total 116126
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191426
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 81
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4162
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3953
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 187912
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 4173312976 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 101153682332 (94.21 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 41
```