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

# Server Metrics 2026-03-19 01:32:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 13442.4 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154127
telemt_connections_bad_total 19068
telemt_connections_current 618
telemt_connections_me_current 618
telemt_handshake_timeouts_total 3222
telemt_upstream_connect_attempt_total 2693
telemt_upstream_connect_success_total 2648
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1983
telemt_me_reconnect_success_total 1977
telemt_me_reader_eof_total 2053
telemt_me_idle_close_by_peer_total 2053
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 46120
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125277
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 792
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1982
telemt_me_writer_restored_same_endpoint_total 1963
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 122509
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 1244906964 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 40647792444 (37.86 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 13446.4 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302702
telemt_connections_bad_total 21163
telemt_connections_current 1543
telemt_connections_me_current 1543
telemt_handshake_timeouts_total 5042
telemt_upstream_connect_attempt_total 2538
telemt_upstream_connect_success_total 2489
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 1818
telemt_me_reconnect_success_total 1811
telemt_me_reader_eof_total 1907
telemt_me_idle_close_by_peer_total 1907
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 94534
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258950
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 931
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 376
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1843
telemt_me_writer_restored_same_endpoint_total 1798
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 258992
telemt_user_connections_current{user="hello"} 1543
telemt_user_octets_from_client{user="hello"} 11162967116 (10.40 GB)
telemt_user_octets_to_client{user="hello"} 98702475076 (91.92 GB)
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 13443.6 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242400
telemt_connections_bad_total 43530
telemt_connections_current 1104
telemt_connections_me_current 1104
telemt_handshake_timeouts_total 6254
telemt_upstream_connect_attempt_total 2597
telemt_upstream_connect_success_total 2597
telemt_upstream_connect_attempts_per_request{bucket="1"} 2597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1293
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1925
telemt_me_reconnect_success_total 1920
telemt_me_reader_eof_total 2018
telemt_me_idle_close_by_peer_total 2018
telemt_me_route_drop_no_conn_total 76424
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185457
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 895
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1948
telemt_me_writer_restored_same_endpoint_total 1904
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 185450
telemt_user_connections_current{user="hello"} 1104
telemt_user_octets_from_client{user="hello"} 2267321344 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 110883799848 (103.27 GB)
telemt_user_unique_ips_current{user="hello"} 481
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 13496.9 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267420
telemt_connections_bad_total 27788
telemt_connections_current 885
telemt_connections_me_current 885
telemt_handshake_timeouts_total 4652
telemt_upstream_connect_attempt_total 2448
telemt_upstream_connect_success_total 2448
telemt_upstream_connect_attempts_per_request{bucket="1"} 2448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1777
telemt_me_reconnect_success_total 1771
telemt_me_reader_eof_total 1850
telemt_me_idle_close_by_peer_total 1850
telemt_me_route_drop_no_conn_total 80886
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187052
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 523
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1791
telemt_me_writer_restored_same_endpoint_total 1747
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 186970
telemt_user_connections_current{user="hello"} 885
telemt_user_octets_from_client{user="hello"} 1787595488 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 63289191664 (58.94 GB)
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 13440.3 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265068
telemt_connections_bad_total 16078
telemt_connections_current 1175
telemt_connections_me_current 1175
telemt_handshake_timeouts_total 8889
telemt_upstream_connect_attempt_total 2500
telemt_upstream_connect_success_total 2487
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1816
telemt_me_reconnect_success_total 1805
telemt_me_reader_eof_total 1890
telemt_me_idle_close_by_peer_total 1890
telemt_me_route_drop_no_conn_total 82228
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202068
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 820
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 509
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1815
telemt_me_writer_restored_same_endpoint_total 1781
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 201991
telemt_user_connections_current{user="hello"} 1175
telemt_user_octets_from_client{user="hello"} 5233733188 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 113926690040 (106.10 GB)
telemt_user_unique_ips_current{user="hello"} 524
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 13451.8 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66500
telemt_connections_bad_total 9214
telemt_connections_current 302
telemt_connections_me_current 302
telemt_handshake_timeouts_total 243
telemt_upstream_connect_attempt_total 3834
telemt_upstream_connect_success_total 3719
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 3834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1967
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 4877
telemt_me_reconnect_success_total 3049
telemt_me_reader_eof_total 3187
telemt_me_idle_close_by_peer_total 3187
telemt_me_route_drop_no_conn_total 25539
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55305
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3097
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3019
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 55305
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 793086276 (756.35 MB)
telemt_user_octets_to_client{user="hello"} 35710515844 (33.26 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 13442.6 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187477
telemt_connections_bad_total 21550
telemt_connections_current 992
telemt_connections_me_current 992
telemt_handshake_timeouts_total 8586
telemt_upstream_connect_attempt_total 2848
telemt_upstream_connect_success_total 2848
telemt_upstream_connect_attempts_per_request{bucket="1"} 2848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2177
telemt_me_reconnect_success_total 2170
telemt_me_reader_eof_total 2274
telemt_me_idle_close_by_peer_total 2274
telemt_me_route_drop_no_conn_total 55798
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152989
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 966
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 580
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2195
telemt_me_writer_restored_same_endpoint_total 2155
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 153012
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 1578753468 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 79679049924 (74.21 GB)
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 79
```