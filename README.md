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

# Server Metrics 2026-03-17 07:15:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 45005.3 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287100
telemt_connections_bad_total 3441
telemt_handshake_timeouts_total 8854
telemt_upstream_connect_attempt_total 9283
telemt_upstream_connect_success_total 9233
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7040
telemt_me_reconnect_success_total 7013
telemt_me_reader_eof_total 7466
telemt_me_idle_close_by_peer_total 7466
telemt_me_route_drop_no_conn_total 87612
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257824
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1956
telemt_desync_full_logged_total 577
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 421
telemt_desync_frames_bucket_total{bucket="3_10"} 994
telemt_desync_frames_bucket_total{bucket="gt_10"} 541
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7086
telemt_me_writer_restored_same_endpoint_total 6992
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 257604
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 3426569888 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 113428200556 (105.64 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 45256.9 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161847
telemt_connections_bad_total 2346
telemt_handshake_timeouts_total 11694
telemt_upstream_connect_attempt_total 12402
telemt_upstream_connect_success_total 12241
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 12402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_reconnect_attempts_total 11167
telemt_me_reconnect_success_total 9985
telemt_me_reader_eof_total 10553
telemt_me_idle_close_by_peer_total 10553
telemt_me_route_drop_no_conn_total 58715
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139941
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 376
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10113
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9969
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 139990
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 1716713812 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 58976766392 (54.93 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 45033.0 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95972
telemt_connections_bad_total 1571
telemt_handshake_timeouts_total 3851
telemt_upstream_connect_attempt_total 11869
telemt_upstream_connect_success_total 11806
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 11869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9612
telemt_me_reconnect_success_total 9557
telemt_me_reader_eof_total 10228
telemt_me_idle_close_by_peer_total 10228
telemt_me_route_drop_no_conn_total 31804
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82093
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9674
telemt_me_writer_restored_same_endpoint_total 9546
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 82050
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 6275980008 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 25796365592 (24.02 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 45092.0 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186592
telemt_connections_bad_total 5826
telemt_handshake_timeouts_total 9886
telemt_upstream_connect_attempt_total 10260
telemt_upstream_connect_success_total 10174
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 10259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 7920
telemt_me_reconnect_success_total 7858
telemt_me_reader_eof_total 8349
telemt_me_idle_close_by_peer_total 8349
telemt_me_route_drop_no_conn_total 56840
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157117
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 292
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 195
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7969
telemt_me_writer_restored_same_endpoint_total 7850
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 157125
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 1659635226 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 72781225417 (67.78 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 45064.1 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127801
telemt_connections_bad_total 38197
telemt_handshake_timeouts_total 2398
telemt_upstream_connect_attempt_total 13736
telemt_upstream_connect_success_total 13560
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 13736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_reconnect_attempts_total 14459
telemt_me_reconnect_success_total 11197
telemt_me_reader_eof_total 11819
telemt_me_idle_close_by_peer_total 11819
telemt_me_route_drop_no_conn_total 33095
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83749
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 80
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 11441
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11189
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 83793
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 844028551 (804.93 MB)
telemt_user_octets_to_client{user="hello"} 39200046918 (36.51 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 45225.2 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301861
telemt_connections_bad_total 42160
telemt_handshake_timeouts_total 2487
telemt_upstream_connect_attempt_total 9305
telemt_upstream_connect_success_total 9257
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 7024
telemt_me_reconnect_success_total 6990
telemt_me_reader_eof_total 7472
telemt_me_idle_close_by_peer_total 7472
telemt_me_route_drop_no_conn_total 232461
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323643
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 347
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7093
telemt_me_writer_restored_same_endpoint_total 6976
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 245579
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 3561107040 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 159816282348 (148.84 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 33231.6 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1507
telemt_connections_bad_total 193
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 16634
telemt_upstream_connect_success_total 16633
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15004
telemt_me_reconnect_success_total 14919
telemt_me_reader_eof_total 16312
telemt_me_idle_close_by_peer_total 16312
telemt_me_route_drop_no_conn_total 180
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1297
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 15052
telemt_me_writer_restored_same_endpoint_total 14919
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 1297
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 209868424 (200.15 MB)
telemt_user_octets_to_client{user="hello"} 13878113260 (12.93 GB)
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 1
```