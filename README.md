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

# Server Metrics 2026-03-17 09:17:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 52339.4 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402545
telemt_connections_bad_total 3639
telemt_handshake_timeouts_total 12017
telemt_upstream_connect_attempt_total 13447
telemt_upstream_connect_success_total 13017
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 13447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 9623
telemt_me_reconnect_success_total 8102
telemt_me_reader_eof_total 8607
telemt_me_idle_close_by_peer_total 8606
telemt_me_route_drop_no_conn_total 126882
telemt_me_route_drop_channel_closed_total 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362396
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2822
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 2041
telemt_desync_frames_bucket_total{bucket="1_2"} 671
telemt_desync_frames_bucket_total{bucket="3_10"} 1294
telemt_desync_frames_bucket_total{bucket="gt_10"} 857
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8267
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8080
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 364391
telemt_user_connections_current{user="hello"} 971
telemt_user_octets_from_client{user="hello"} 5081424207 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 143805158919 (133.93 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 52590.2 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218604
telemt_connections_bad_total 2377
telemt_handshake_timeouts_total 12471
telemt_upstream_connect_attempt_total 13994
telemt_upstream_connect_success_total 13806
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 13994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 17182
telemt_me_reconnect_success_total 11195
telemt_me_reader_eof_total 11944
telemt_me_idle_close_by_peer_total 11944
telemt_me_route_drop_no_conn_total 80010
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193009
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 516
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 328
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11495
telemt_me_refill_failed_total 186
telemt_me_writer_restored_same_endpoint_total 11179
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 193014
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 2321034296 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 76483451592 (71.23 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 52366.6 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135109
telemt_connections_bad_total 7573
telemt_handshake_timeouts_total 8858
telemt_upstream_connect_attempt_total 13925
telemt_upstream_connect_success_total 13852
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 13925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12161
telemt_me_reconnect_success_total 11195
telemt_me_reader_eof_total 11966
telemt_me_idle_close_by_peer_total 11966
telemt_me_route_drop_no_conn_total 41299
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109454
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 313
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11370
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11184
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 109378
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 7248186484 (6.75 GB)
telemt_user_octets_to_client{user="hello"} 34506013984 (32.14 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 52425.6 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294153
telemt_connections_bad_total 6181
telemt_handshake_timeouts_total 10714
telemt_upstream_connect_attempt_total 11949
telemt_upstream_connect_success_total 11840
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 11949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10228
telemt_me_reconnect_success_total 9149
telemt_me_reader_eof_total 9738
telemt_me_idle_close_by_peer_total 9738
telemt_me_route_drop_no_conn_total 81139
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234274
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 487
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 305
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9323
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9141
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 234229
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 2521882598 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 96010959801 (89.42 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 52397.4 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166092
telemt_connections_bad_total 45078
telemt_handshake_timeouts_total 2746
telemt_upstream_connect_attempt_total 15982
telemt_upstream_connect_success_total 15771
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 15982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_reconnect_attempts_total 20135
telemt_me_reconnect_success_total 13023
telemt_me_reader_eof_total 13811
telemt_me_idle_close_by_peer_total 13811
telemt_me_route_drop_no_conn_total 43411
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113195
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 346
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 257
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 13410
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 13015
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 113223
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 1776927463 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 51504411730 (47.97 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 52558.7 (14h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393757
telemt_connections_bad_total 46863
telemt_handshake_timeouts_total 3936
telemt_upstream_connect_attempt_total 10776
telemt_upstream_connect_success_total 10718
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11974
telemt_me_reconnect_success_total 8095
telemt_me_reader_eof_total 8748
telemt_me_idle_close_by_peer_total 8748
telemt_me_route_drop_no_conn_total 266522
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399054
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 547
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 326
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8337
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8081
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 320950
telemt_user_connections_current{user="hello"} 840
telemt_user_octets_from_client{user="hello"} 4633599508 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 180187027352 (167.81 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 325.6 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 581
telemt_upstream_connect_attempt_total 205
telemt_upstream_connect_success_total 187
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 27
telemt_me_reconnect_success_total 10
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 109
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 511
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 5275709 (5.03 MB)
telemt_user_octets_to_client{user="hello"} 1243007578 (1.16 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 4
```