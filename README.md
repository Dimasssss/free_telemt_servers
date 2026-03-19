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

# Server Metrics 2026-03-19 12:57:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 966.7 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38634
telemt_connections_bad_total 1576
telemt_connections_current 1586
telemt_connections_me_current 1586
telemt_handshake_timeouts_total 614
telemt_upstream_connect_attempt_total 123
telemt_upstream_connect_success_total 104
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 29
telemt_me_reconnect_success_total 13
telemt_me_route_drop_no_conn_total 16419
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34238
telemt_me_writer_pick_total{mode="p2c",result="full"} 54
telemt_me_writer_pick_total{mode="p2c",result="closed"} 152
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 2
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 220
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 33830
telemt_user_connections_current{user="hello"} 1586
telemt_user_octets_from_client{user="hello"} 597393444 (569.72 MB)
telemt_user_octets_to_client{user="hello"} 10061921968 (9.37 GB)
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 876.8 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139132
telemt_connections_bad_total 1586
telemt_connections_current 3574
telemt_connections_me_current 3574
telemt_handshake_timeouts_total 755
telemt_upstream_connect_attempt_total 1475
telemt_upstream_connect_success_total 1471
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 190
telemt_me_reconnect_success_total 187
telemt_me_reader_eof_total 134
telemt_me_idle_close_by_peer_total 134
telemt_me_route_drop_no_conn_total 207972
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128562
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 268
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 158
telemt_me_writer_restored_same_endpoint_total 132
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_user_connections_total{user="hello"} 129588
telemt_user_connections_current{user="hello"} 3574
telemt_user_octets_from_client{user="hello"} 697853282 (665.52 MB)
telemt_user_octets_to_client{user="hello"} 15886619206 (14.80 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1169
telemt_user_unique_ips_recent_window{user="hello"} 907
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 854.8 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99100
telemt_connections_bad_total 4700
telemt_connections_current 2931
telemt_connections_me_current 2931
telemt_handshake_timeouts_total 972
telemt_upstream_connect_attempt_total 185
telemt_upstream_connect_success_total 184
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 119
telemt_me_reconnect_success_total 119
telemt_me_reader_eof_total 33
telemt_me_idle_close_by_peer_total 33
telemt_me_route_drop_no_conn_total 46375
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67571
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 283
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 55
telemt_me_writer_restored_same_endpoint_total 118
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5542
telemt_user_connections_total{user="hello"} 67394
telemt_user_connections_current{user="hello"} 2931
telemt_user_octets_from_client{user="hello"} 516504088 (492.58 MB)
telemt_user_octets_to_client{user="hello"} 18212138320 (16.96 GB)
telemt_user_unique_ips_current{user="hello"} 1068
telemt_user_unique_ips_recent_window{user="hello"} 537
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 842.4 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80881
telemt_connections_bad_total 12626
telemt_connections_current 3104
telemt_connections_me_current 3104
telemt_handshake_timeouts_total 1272
telemt_upstream_connect_attempt_total 158
telemt_upstream_connect_success_total 154
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 91
telemt_me_reconnect_success_total 91
telemt_me_reader_eof_total 46
telemt_me_idle_close_by_peer_total 46
telemt_me_route_drop_no_conn_total 28142
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60507
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 223
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 69
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 60367
telemt_user_connections_current{user="hello"} 3104
telemt_user_octets_from_client{user="hello"} 894187036 (852.76 MB)
telemt_user_octets_to_client{user="hello"} 13983925996 (13.02 GB)
telemt_user_unique_ips_current{user="hello"} 1003
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 54565.6 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3637237
telemt_connections_bad_total 731784
telemt_connections_current 3703
telemt_connections_me_current 3703
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 71707
telemt_upstream_connect_attempt_total 61505
telemt_upstream_connect_success_total 59024
telemt_upstream_connect_fail_total 2481
telemt_upstream_connect_attempts_per_request{bucket="1"} 61505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2481
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70168
telemt_me_reconnect_success_total 7117
telemt_me_reader_eof_total 7438
telemt_me_idle_close_by_peer_total 7435
telemt_me_route_drop_no_conn_total 1615704
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2432515
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10445
telemt_desync_full_logged_total 3253
telemt_desync_suppressed_total 7192
telemt_desync_frames_bucket_total{bucket="1_2"} 1899
telemt_desync_frames_bucket_total{bucket="3_10"} 4433
telemt_desync_frames_bucket_total{bucket="gt_10"} 4113
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7237
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7093
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 2481411
telemt_user_connections_current{user="hello"} 3703
telemt_user_octets_from_client{user="hello"} 39933370319 (37.19 GB)
telemt_user_octets_to_client{user="hello"} 904943434028 (842.79 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1135
telemt_user_unique_ips_recent_window{user="hello"} 584
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 808.1 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20497
telemt_connections_bad_total 542
telemt_connections_current 964
telemt_connections_me_current 964
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 81
telemt_upstream_connect_success_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 81
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 15
telemt_me_route_drop_no_conn_total 15975
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19038
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 367
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 19040
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 182841844 (174.37 MB)
telemt_user_octets_to_client{user="hello"} 3600635912 (3.35 GB)
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 806.9 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58613
telemt_connections_bad_total 5305
telemt_connections_current 3065
telemt_connections_me_current 3065
telemt_handshake_timeouts_total 357
telemt_upstream_connect_attempt_total 103
telemt_upstream_connect_success_total 101
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 39
telemt_me_reconnect_success_total 38
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 15618
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50269
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 39
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 50262
telemt_user_connections_current{user="hello"} 3065
telemt_user_octets_from_client{user="hello"} 493597256 (470.73 MB)
telemt_user_octets_to_client{user="hello"} 17026425356 (15.86 GB)
telemt_user_unique_ips_current{user="hello"} 1040
telemt_user_unique_ips_recent_window{user="hello"} 439
```