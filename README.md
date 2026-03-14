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

# Server Metrics 2026-03-14 15:06:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 6606.1 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39452
telemt_connections_bad_total 7407
telemt_handshake_timeouts_total 207
telemt_upstream_connect_attempt_total 1802
telemt_upstream_connect_success_total 1800
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 881
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1423
telemt_me_reconnect_success_total 1402
telemt_me_reader_eof_total 1453
telemt_me_idle_close_by_peer_total 1453
telemt_me_route_drop_no_conn_total 14926
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31025
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1432
telemt_me_writer_restored_same_endpoint_total 1384
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 30961
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 460758392 (439.41 MB)
telemt_user_octets_to_client{user="hello"} 11457788972 (10.67 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 6604.8 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15442
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 1950
telemt_upstream_connect_success_total 1924
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 4089
telemt_me_reconnect_success_total 1533
telemt_me_reader_eof_total 1636
telemt_me_idle_close_by_peer_total 1636
telemt_me_route_drop_no_conn_total 8358
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14404
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1635
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1528
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 14387
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 181516188 (173.11 MB)
telemt_user_octets_to_client{user="hello"} 4183274280 (3.90 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 6609.0 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15040
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 258
telemt_upstream_connect_attempt_total 3155
telemt_upstream_connect_success_total 3131
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 3155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 96299
telemt_me_reconnect_success_total 2422
telemt_me_reader_eof_total 2537
telemt_me_idle_close_by_peer_total 2537
telemt_me_route_drop_no_conn_total 5852
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13525
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2541
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 2384
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 13823
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 488744909 (466.10 MB)
telemt_user_octets_to_client{user="hello"} 6761513386 (6.30 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 6613.8 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20935
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 153
telemt_upstream_connect_attempt_total 1728
telemt_upstream_connect_success_total 1721
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1344
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 1363
telemt_me_idle_close_by_peer_total 1363
telemt_me_route_drop_no_conn_total 10342
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19859
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 190
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1339
telemt_me_writer_restored_same_endpoint_total 1332
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 19742
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 229840064 (219.19 MB)
telemt_user_octets_to_client{user="hello"} 6706037860 (6.25 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 6606.7 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14846
telemt_connections_bad_total 1367
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 1521
telemt_upstream_connect_success_total 1495
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 891
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 7608
telemt_me_reconnect_success_total 1102
telemt_me_reader_eof_total 1281
telemt_me_idle_close_by_peer_total 1281
telemt_me_route_drop_no_conn_total 5227
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12502
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 1302
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1098
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 12498
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 107455808 (102.48 MB)
telemt_user_octets_to_client{user="hello"} 3364386628 (3.13 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 6606.9 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52463
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 374
telemt_upstream_connect_attempt_total 1443
telemt_upstream_connect_success_total 1409
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 1443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1043
telemt_me_reconnect_success_total 1014
telemt_me_reader_eof_total 1029
telemt_me_idle_close_by_peer_total 1029
telemt_me_route_drop_no_conn_total 26711
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48481
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1020
telemt_me_writer_restored_same_endpoint_total 1010
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 48389
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 799765812 (762.72 MB)
telemt_user_octets_to_client{user="hello"} 18977505212 (17.67 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 81
```