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

# Server Metrics 2026-03-17 04:06:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 33693.7 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176080
telemt_connections_bad_total 2507
telemt_handshake_timeouts_total 6238
telemt_upstream_connect_attempt_total 7277
telemt_upstream_connect_success_total 7235
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 7277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5563
telemt_me_reconnect_success_total 5547
telemt_me_reader_eof_total 5899
telemt_me_idle_close_by_peer_total 5899
telemt_me_route_drop_no_conn_total 56003
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159713
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1003
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 651
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5597
telemt_me_writer_restored_same_endpoint_total 5526
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 159523
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 2269919412 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 72846254324 (67.84 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 33945.2 (9h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98271
telemt_connections_bad_total 1940
telemt_handshake_timeouts_total 3464
telemt_upstream_connect_attempt_total 9585
telemt_upstream_connect_success_total 9462
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 9585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_reconnect_attempts_total 8951
telemt_me_reconnect_success_total 7782
telemt_me_reader_eof_total 8225
telemt_me_idle_close_by_peer_total 8225
telemt_me_route_drop_no_conn_total 40770
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88855
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7892
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7766
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 88826
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 1232665624 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 40195869552 (37.44 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 33721.8 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63929
telemt_connections_bad_total 797
telemt_handshake_timeouts_total 2360
telemt_upstream_connect_attempt_total 9042
telemt_upstream_connect_success_total 8993
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 9042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 7331
telemt_me_reconnect_success_total 7289
telemt_me_reader_eof_total 7809
telemt_me_idle_close_by_peer_total 7809
telemt_me_route_drop_no_conn_total 21029
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54207
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7381
telemt_me_writer_restored_same_endpoint_total 7278
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 54190
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 5723566048 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 18640558860 (17.36 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 33780.7 (9h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101192
telemt_connections_bad_total 3414
telemt_handshake_timeouts_total 2078
telemt_upstream_connect_attempt_total 7799
telemt_upstream_connect_success_total 7732
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 7799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 6074
telemt_me_reconnect_success_total 6029
telemt_me_reader_eof_total 6415
telemt_me_idle_close_by_peer_total 6415
telemt_me_route_drop_no_conn_total 34402
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92765
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6117
telemt_me_writer_restored_same_endpoint_total 6022
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 92749
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 1040789072 (992.57 MB)
telemt_user_octets_to_client{user="hello"} 44804517188 (41.73 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 33752.5 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74745
telemt_connections_bad_total 16824
telemt_handshake_timeouts_total 1386
telemt_upstream_connect_attempt_total 9942
telemt_upstream_connect_success_total 9818
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 9942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_reconnect_attempts_total 10374
telemt_me_reconnect_success_total 8123
telemt_me_reader_eof_total 8582
telemt_me_idle_close_by_peer_total 8582
telemt_me_route_drop_no_conn_total 21621
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54442
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 8310
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 8115
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 54438
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 617185164 (588.59 MB)
telemt_user_octets_to_client{user="hello"} 22526358088 (20.98 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 33913.7 (9h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197633
telemt_connections_bad_total 23642
telemt_handshake_timeouts_total 1202
telemt_upstream_connect_attempt_total 7089
telemt_upstream_connect_success_total 7049
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 7089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5385
telemt_me_reconnect_success_total 5366
telemt_me_reader_eof_total 5749
telemt_me_idle_close_by_peer_total 5749
telemt_me_route_drop_no_conn_total 186845
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244648
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 164
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5438
telemt_me_writer_restored_same_endpoint_total 5356
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 166902
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 2568266944 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 132860262144 (123.74 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 21920.1 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 11065
telemt_upstream_connect_success_total 11065
telemt_upstream_connect_attempts_per_request{bucket="1"} 11065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 9956
telemt_me_reconnect_success_total 9901
telemt_me_reader_eof_total 10887
telemt_me_idle_close_by_peer_total 10887
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 9999
telemt_me_writer_restored_same_endpoint_total 9901
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```