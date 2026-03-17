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

# Server Metrics 2026-03-17 03:41:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 32168.2 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167389
telemt_connections_bad_total 2417
telemt_handshake_timeouts_total 5660
telemt_upstream_connect_attempt_total 6884
telemt_upstream_connect_success_total 6843
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5259
telemt_me_reconnect_success_total 5243
telemt_me_reader_eof_total 5579
telemt_me_idle_close_by_peer_total 5579
telemt_me_route_drop_no_conn_total 53604
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152124
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 905
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 463
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5291
telemt_me_writer_restored_same_endpoint_total 5222
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 151933
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 2022632236 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 69593508096 (64.81 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 32419.4 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93789
telemt_connections_bad_total 1864
telemt_handshake_timeouts_total 3388
telemt_upstream_connect_attempt_total 9162
telemt_upstream_connect_success_total 9041
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 9162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_reconnect_attempts_total 8616
telemt_me_reconnect_success_total 7449
telemt_me_reader_eof_total 7840
telemt_me_idle_close_by_peer_total 7840
telemt_me_route_drop_no_conn_total 38829
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84786
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 218
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7556
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7433
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 84729
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 1181895280 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 38633437268 (35.98 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 32195.8 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60901
telemt_connections_bad_total 789
telemt_handshake_timeouts_total 2145
telemt_upstream_connect_attempt_total 8621
telemt_upstream_connect_success_total 8574
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 8621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 6998
telemt_me_reconnect_success_total 6958
telemt_me_reader_eof_total 7447
telemt_me_idle_close_by_peer_total 7447
telemt_me_route_drop_no_conn_total 19582
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51556
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
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 7048
telemt_me_writer_restored_same_endpoint_total 6947
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 51541
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 5591556308 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 18231206288 (16.98 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 32255.0 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95768
telemt_connections_bad_total 3413
telemt_handshake_timeouts_total 1809
telemt_upstream_connect_attempt_total 7440
telemt_upstream_connect_success_total 7375
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 7440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3875
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 5803
telemt_me_reconnect_success_total 5763
telemt_me_reader_eof_total 6127
telemt_me_idle_close_by_peer_total 6127
telemt_me_route_drop_no_conn_total 32750
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87779
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 159
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5845
telemt_me_writer_restored_same_endpoint_total 5756
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 87763
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 988392084 (942.60 MB)
telemt_user_octets_to_client{user="hello"} 41757162160 (38.89 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 32226.9 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71696
telemt_connections_bad_total 16472
telemt_handshake_timeouts_total 1358
telemt_upstream_connect_attempt_total 9548
telemt_upstream_connect_success_total 9428
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 9548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 10071
telemt_me_reconnect_success_total 7821
telemt_me_reader_eof_total 8253
telemt_me_idle_close_by_peer_total 8253
telemt_me_route_drop_no_conn_total 20708
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51869
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 8006
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 7813
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 51864
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 604571920 (576.56 MB)
telemt_user_octets_to_client{user="hello"} 22174934868 (20.65 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 32388.1 (8h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186700
telemt_connections_bad_total 19251
telemt_handshake_timeouts_total 1175
telemt_upstream_connect_attempt_total 6714
telemt_upstream_connect_success_total 6677
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5100
telemt_me_reconnect_success_total 5083
telemt_me_reader_eof_total 5445
telemt_me_idle_close_by_peer_total 5445
telemt_me_route_drop_no_conn_total 183917
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238236
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 145
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5155
telemt_me_writer_restored_same_endpoint_total 5073
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 160490
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 2487928420 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 128383129020 (119.57 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 20394.5 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 10280
telemt_upstream_connect_success_total 10280
telemt_upstream_connect_attempts_per_request{bucket="1"} 10280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 9259
telemt_me_reconnect_success_total 9208
telemt_me_reader_eof_total 10106
telemt_me_idle_close_by_peer_total 10106
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 9297
telemt_me_writer_restored_same_endpoint_total 9208
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```