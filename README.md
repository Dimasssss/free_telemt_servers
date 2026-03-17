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

# Server Metrics 2026-03-17 05:23:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 38287.3 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209414
telemt_connections_bad_total 3165
telemt_handshake_timeouts_total 7237
telemt_upstream_connect_attempt_total 8100
telemt_upstream_connect_success_total 8057
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 8100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6170
telemt_me_reconnect_success_total 6147
telemt_me_reader_eof_total 6539
telemt_me_idle_close_by_peer_total 6539
telemt_me_route_drop_no_conn_total 65942
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188918
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1210
telemt_desync_full_logged_total 420
telemt_desync_suppressed_total 790
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 611
telemt_desync_frames_bucket_total{bucket="gt_10"} 320
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6208
telemt_me_writer_restored_same_endpoint_total 6126
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 188715
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 2640462580 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 85819642800 (79.93 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 38538.4 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123128
telemt_connections_bad_total 2192
telemt_handshake_timeouts_total 10086
telemt_upstream_connect_attempt_total 10637
telemt_upstream_connect_success_total 10500
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 10637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 9774
telemt_me_reconnect_success_total 8602
telemt_me_reader_eof_total 9104
telemt_me_idle_close_by_peer_total 9104
telemt_me_route_drop_no_conn_total 47365
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106278
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 299
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 195
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8719
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8586
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 106288
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 1379408944 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 45969414412 (42.81 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 38315.7 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74299
telemt_connections_bad_total 1067
telemt_handshake_timeouts_total 2502
telemt_upstream_connect_attempt_total 10260
telemt_upstream_connect_success_total 10205
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8323
telemt_me_reconnect_success_total 8279
telemt_me_reader_eof_total 8868
telemt_me_idle_close_by_peer_total 8868
telemt_me_route_drop_no_conn_total 24773
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63524
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8379
telemt_me_writer_restored_same_endpoint_total 8268
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 63508
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 5951023316 (5.54 GB)
telemt_user_octets_to_client{user="hello"} 20580084364 (19.17 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 38374.0 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122714
telemt_connections_bad_total 3691
telemt_handshake_timeouts_total 3555
telemt_upstream_connect_attempt_total 8744
telemt_upstream_connect_success_total 8670
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 8744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4562
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 6759
telemt_me_reconnect_success_total 6707
telemt_me_reader_eof_total 7144
telemt_me_idle_close_by_peer_total 7144
telemt_me_route_drop_no_conn_total 41186
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111833
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 214
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6806
telemt_me_writer_restored_same_endpoint_total 6700
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 111851
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 1238571122 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 53155878077 (49.51 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 38345.8 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93531
telemt_connections_bad_total 25182
telemt_handshake_timeouts_total 1942
telemt_upstream_connect_attempt_total 11387
telemt_upstream_connect_success_total 11238
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 11387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_reconnect_attempts_total 11475
telemt_me_reconnect_success_total 9215
telemt_me_reader_eof_total 9741
telemt_me_idle_close_by_peer_total 9741
telemt_me_route_drop_no_conn_total 25172
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63860
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9407
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9207
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 63958
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 721735707 (688.30 MB)
telemt_user_octets_to_client{user="hello"} 27615376718 (25.72 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 38506.7 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230136
telemt_connections_bad_total 29607
telemt_handshake_timeouts_total 1723
telemt_upstream_connect_attempt_total 7916
telemt_upstream_connect_success_total 7875
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 7916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5994
telemt_me_reconnect_success_total 5967
telemt_me_reader_eof_total 6400
telemt_me_idle_close_by_peer_total 6400
telemt_me_route_drop_no_conn_total 199115
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269008
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 223
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6054
telemt_me_writer_restored_same_endpoint_total 5957
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 191260
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 2976376084 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 145014723696 (135.06 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 26513.4 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 13281
telemt_upstream_connect_success_total 13281
telemt_upstream_connect_attempts_per_request{bucket="1"} 13281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 11956
telemt_me_reconnect_success_total 11892
telemt_me_reader_eof_total 13066
telemt_me_idle_close_by_peer_total 13066
telemt_me_route_drop_no_conn_total 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 12002
telemt_me_writer_restored_same_endpoint_total 11892
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 223
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 158418728 (151.08 MB)
telemt_user_octets_to_client{user="hello"} 92584284 (88.30 MB)
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```