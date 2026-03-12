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

# Server Metrics 2026-03-12 12:43:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18593.6 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99108
telemt_connections_bad_total 541
telemt_handshake_timeouts_total 3494
telemt_upstream_connect_attempt_total 4537
telemt_upstream_connect_success_total 4516
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2488
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 207
telemt_me_reconnect_attempts_total 3572
telemt_me_reconnect_success_total 3550
telemt_me_reader_eof_total 3712
telemt_me_idle_close_by_peer_total 3711
telemt_me_route_drop_no_conn_total 27561
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88813
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 413
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 254
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3574
telemt_me_writer_restored_same_endpoint_total 3534
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 88780
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 1237021616 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 29439797420 (27.42 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 18486.8 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39992
telemt_connections_bad_total 334
telemt_handshake_timeouts_total 311
telemt_upstream_connect_attempt_total 5554
telemt_upstream_connect_success_total 5413
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 5554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 20288
telemt_me_reconnect_success_total 4465
telemt_me_reader_eof_total 5002
telemt_me_idle_close_by_peer_total 5002
telemt_me_route_drop_no_conn_total 17171
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38037
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 4975
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 4450
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 38038
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 444345084 (423.76 MB)
telemt_user_octets_to_client{user="hello"} 9856933364 (9.18 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 18450.2 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54011
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 523
telemt_upstream_connect_attempt_total 5082
telemt_upstream_connect_success_total 5082
telemt_upstream_connect_attempts_per_request{bucket="1"} 5082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 4138
telemt_me_reconnect_success_total 4107
telemt_me_reader_eof_total 4330
telemt_me_idle_close_by_peer_total 4330
telemt_me_route_drop_no_conn_total 18915
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50857
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4129
telemt_me_writer_restored_same_endpoint_total 4087
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 50840
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 1736481776 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 32171200004 (29.96 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 18426.1 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68909
telemt_connections_bad_total 1082
telemt_handshake_timeouts_total 325
telemt_upstream_connect_attempt_total 4969
telemt_upstream_connect_success_total 4845
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 4969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 186
telemt_me_reconnect_attempts_total 10423
telemt_me_reconnect_success_total 3879
telemt_me_reader_eof_total 4207
telemt_me_idle_close_by_peer_total 4207
telemt_me_route_drop_no_conn_total 23208
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4131
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3871
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 63168
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1103875424 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 30742265776 (28.63 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18395.4 (5h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38561
telemt_connections_bad_total 3487
telemt_handshake_timeouts_total 640
telemt_upstream_connect_attempt_total 7447
telemt_upstream_connect_success_total 7221
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 7447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 23146
telemt_me_reconnect_success_total 3588
telemt_me_reader_eof_total 4196
telemt_me_idle_close_by_peer_total 4196
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 11221
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30769
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 396
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4220
telemt_me_refill_failed_total 612
telemt_me_writer_restored_same_endpoint_total 3571
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 33439
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 233528203 (222.71 MB)
telemt_user_octets_to_client{user="hello"} 8402835708 (7.83 GB)
telemt_user_msgs_from_client{user="hello"} 30002
telemt_user_msgs_to_client{user="hello"} 119207
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 18382.3 (5h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103968
telemt_connections_bad_total 761
telemt_handshake_timeouts_total 930
telemt_upstream_connect_attempt_total 3715
telemt_upstream_connect_success_total 3695
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 3715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 2766
telemt_me_reconnect_success_total 2739
telemt_me_reader_eof_total 2883
telemt_me_idle_close_by_peer_total 2883
telemt_me_route_drop_no_conn_total 42948
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98885
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 209
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2775
telemt_me_writer_restored_same_endpoint_total 2732
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 98852
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 2461965680 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 47245183900 (44.00 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 51
```