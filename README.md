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

# Server Metrics 2026-03-16 20:45:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 7205.5 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50944
telemt_connections_bad_total 489
telemt_handshake_timeouts_total 2683
telemt_upstream_connect_attempt_total 1310
telemt_upstream_connect_success_total 1299
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 721
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 929
telemt_me_reconnect_success_total 926
telemt_me_reader_eof_total 944
telemt_me_idle_close_by_peer_total 944
telemt_me_route_drop_no_conn_total 17055
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45795
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 213
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 922
telemt_me_writer_restored_same_endpoint_total 905
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 45750
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 872121032 (831.72 MB)
telemt_user_octets_to_client{user="hello"} 28398558976 (26.45 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 7456.8 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41272
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 1919
telemt_upstream_connect_attempt_total 1612
telemt_upstream_connect_success_total 1588
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1177
telemt_me_reconnect_success_total 1174
telemt_me_reader_eof_total 1216
telemt_me_idle_close_by_peer_total 1216
telemt_me_route_drop_no_conn_total 15851
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37368
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1193
telemt_me_writer_restored_same_endpoint_total 1158
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 37352
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 552966096 (527.35 MB)
telemt_user_octets_to_client{user="hello"} 14167567132 (13.19 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 7232.9 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21839
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 1594
telemt_upstream_connect_success_total 1581
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1213
telemt_me_reconnect_success_total 1196
telemt_me_reader_eof_total 1240
telemt_me_idle_close_by_peer_total 1240
telemt_me_route_drop_no_conn_total 7164
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20803
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1208
telemt_me_writer_restored_same_endpoint_total 1185
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 20799
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 551889796 (526.32 MB)
telemt_user_octets_to_client{user="hello"} 8253261368 (7.69 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 7292.2 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43915
telemt_connections_bad_total 2927
telemt_handshake_timeouts_total 358
telemt_upstream_connect_attempt_total 1486
telemt_upstream_connect_success_total 1466
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1057
telemt_me_reconnect_success_total 1045
telemt_me_reader_eof_total 1077
telemt_me_idle_close_by_peer_total 1077
telemt_me_route_drop_no_conn_total 13307
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39327
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1057
telemt_me_writer_restored_same_endpoint_total 1038
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 39320
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 608442544 (580.26 MB)
telemt_user_octets_to_client{user="hello"} 13759598792 (12.81 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 7264.2 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28102
telemt_connections_bad_total 8252
telemt_handshake_timeouts_total 166
telemt_upstream_connect_attempt_total 1818
telemt_upstream_connect_success_total 1792
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 2493
telemt_me_reconnect_success_total 1399
telemt_me_reader_eof_total 1439
telemt_me_idle_close_by_peer_total 1439
telemt_me_route_drop_no_conn_total 7556
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18639
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1434
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 1391
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 18637
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 192827224 (183.89 MB)
telemt_user_octets_to_client{user="hello"} 6422962420 (5.98 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 7425.4 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63949
telemt_connections_bad_total 714
telemt_handshake_timeouts_total 664
telemt_upstream_connect_attempt_total 1384
telemt_upstream_connect_success_total 1374
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 963
telemt_me_reconnect_success_total 961
telemt_me_reader_eof_total 1003
telemt_me_idle_close_by_peer_total 1003
telemt_me_route_drop_no_conn_total 27026
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60265
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 977
telemt_me_writer_restored_same_endpoint_total 951
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 60258
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 1246497976 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 31820695804 (29.64 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 53
```