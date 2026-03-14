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

# Server Metrics 2026-03-14 23:26:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 4337.9 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8542
telemt_connections_bad_total 240
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 1115
telemt_upstream_connect_success_total 1109
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 873
telemt_me_reconnect_success_total 868
telemt_me_reader_eof_total 882
telemt_me_idle_close_by_peer_total 882
telemt_me_route_drop_no_conn_total 2451
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7758
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 861
telemt_me_writer_restored_same_endpoint_total 837
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 7757
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 77525884 (73.93 MB)
telemt_user_octets_to_client{user="hello"} 2211626536 (2.06 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 4344.5 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3692
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 1238
telemt_upstream_connect_success_total 1238
telemt_upstream_connect_attempts_per_request{bucket="1"} 1238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 694
telemt_me_reconnect_attempts_total 996
telemt_me_reconnect_success_total 994
telemt_me_reader_eof_total 1031
telemt_me_idle_close_by_peer_total 1031
telemt_me_route_drop_no_conn_total 1307
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3463
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 995
telemt_me_writer_restored_same_endpoint_total 978
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 3464
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 34205508 (32.62 MB)
telemt_user_octets_to_client{user="hello"} 560146888 (534.20 MB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 4337.1 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4251
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 1139
telemt_upstream_connect_success_total 1138
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 900
telemt_me_reconnect_success_total 891
telemt_me_reader_eof_total 936
telemt_me_idle_close_by_peer_total 936
telemt_me_route_drop_no_conn_total 1315
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4020
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 888
telemt_me_writer_restored_same_endpoint_total 887
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 4012
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 1017963628 (970.81 MB)
telemt_user_octets_to_client{user="hello"} 8615145288 (8.02 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 4336.8 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3938
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 1059
telemt_upstream_connect_success_total 1058
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 824
telemt_me_reconnect_success_total 819
telemt_me_reader_eof_total 839
telemt_me_idle_close_by_peer_total 839
telemt_me_route_drop_no_conn_total 1837
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3801
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 817
telemt_me_writer_restored_same_endpoint_total 808
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 3801
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 77290668 (73.71 MB)
telemt_user_octets_to_client{user="hello"} 4631090028 (4.31 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 4337.0 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5602
telemt_connections_bad_total 1041
telemt_handshake_timeouts_total 327
telemt_upstream_connect_attempt_total 1593
telemt_upstream_connect_success_total 1571
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 1402
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1339
telemt_me_route_drop_no_conn_total 1148
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4131
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1326
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1322
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 4126
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 45209332 (43.11 MB)
telemt_user_octets_to_client{user="hello"} 3552963884 (3.31 GB)
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 4336.0 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14321
telemt_connections_bad_total 370
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 1010
telemt_upstream_connect_success_total 1006
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 768
telemt_me_reconnect_success_total 766
telemt_me_reader_eof_total 764
telemt_me_idle_close_by_peer_total 764
telemt_me_route_drop_no_conn_total 6797
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13450
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 745
telemt_me_writer_restored_same_endpoint_total 739
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 13449
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 269280608 (256.81 MB)
telemt_user_octets_to_client{user="hello"} 11345506236 (10.57 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 34
```