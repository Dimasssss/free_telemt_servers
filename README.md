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

# Server Metrics 2026-03-17 01:29:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 24231.6 (6h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134814
telemt_connections_bad_total 2097
telemt_handshake_timeouts_total 5141
telemt_upstream_connect_attempt_total 5065
telemt_upstream_connect_success_total 5035
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 5065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3842
telemt_me_reconnect_success_total 3828
telemt_me_reader_eof_total 4066
telemt_me_idle_close_by_peer_total 4066
telemt_me_route_drop_no_conn_total 41011
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121888
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 672
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 338
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3858
telemt_me_writer_restored_same_endpoint_total 3807
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 121815
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 1737638308 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 57078992512 (53.16 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 24482.9 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78431
telemt_connections_bad_total 977
telemt_handshake_timeouts_total 2913
telemt_upstream_connect_attempt_total 6017
telemt_upstream_connect_success_total 5940
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 6017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_reconnect_attempts_total 4711
telemt_me_reconnect_success_total 4699
telemt_me_reader_eof_total 4971
telemt_me_idle_close_by_peer_total 4971
telemt_me_route_drop_no_conn_total 31680
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71332
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 151
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4751
telemt_me_writer_restored_same_endpoint_total 4683
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 71275
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 1088241012 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 34217017180 (31.87 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 24259.2 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49792
telemt_connections_bad_total 496
telemt_handshake_timeouts_total 1817
telemt_upstream_connect_attempt_total 6543
telemt_upstream_connect_success_total 6503
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 6543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 5316
telemt_me_reconnect_success_total 5286
telemt_me_reader_eof_total 5644
telemt_me_idle_close_by_peer_total 5644
telemt_me_route_drop_no_conn_total 15305
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41847
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5347
telemt_me_writer_restored_same_endpoint_total 5275
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 41832
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 4472817364 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 15370605216 (14.31 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 24318.4 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77804
telemt_connections_bad_total 3055
telemt_handshake_timeouts_total 475
telemt_upstream_connect_attempt_total 5561
telemt_upstream_connect_success_total 5510
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 5561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 4326
telemt_me_reconnect_success_total 4296
telemt_me_reader_eof_total 4550
telemt_me_idle_close_by_peer_total 4550
telemt_me_route_drop_no_conn_total 26479
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72158
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 145
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4352
telemt_me_writer_restored_same_endpoint_total 4289
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 72142
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 875841772 (835.27 MB)
telemt_user_octets_to_client{user="hello"} 31087269088 (28.95 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 24290.5 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58039
telemt_connections_bad_total 14990
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 6890
telemt_upstream_connect_success_total 6796
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 6890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 6708
telemt_me_reconnect_success_total 5586
telemt_me_reader_eof_total 5856
telemt_me_idle_close_by_peer_total 5856
telemt_me_route_drop_no_conn_total 16509
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41039
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 5719
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 5578
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 41034
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 312502076 (298.03 MB)
telemt_user_octets_to_client{user="hello"} 13722403604 (12.78 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 24451.2 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144319
telemt_connections_bad_total 4527
telemt_handshake_timeouts_total 1005
telemt_upstream_connect_attempt_total 5042
telemt_upstream_connect_success_total 5013
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 5042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 3780
telemt_me_reconnect_success_total 3767
telemt_me_reader_eof_total 4036
telemt_me_idle_close_by_peer_total 4036
telemt_me_route_drop_no_conn_total 169074
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211550
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 130
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3820
telemt_me_writer_restored_same_endpoint_total 3757
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 133805
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 2249650456 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 111656211376 (103.99 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 12457.9 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 5922
telemt_upstream_connect_success_total 5921
telemt_upstream_connect_attempts_per_request{bucket="1"} 5921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 5293
telemt_me_reconnect_success_total 5261
telemt_me_reader_eof_total 5773
telemt_me_idle_close_by_peer_total 5773
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5310
telemt_me_writer_restored_same_endpoint_total 5261
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```