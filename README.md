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

# Server Metrics 2026-03-17 05:38:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 39203.6 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218681
telemt_connections_bad_total 3214
telemt_handshake_timeouts_total 7338
telemt_upstream_connect_attempt_total 8281
telemt_upstream_connect_success_total 8238
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 8281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6307
telemt_me_reconnect_success_total 6284
telemt_me_reader_eof_total 6686
telemt_me_idle_close_by_peer_total 6686
telemt_me_route_drop_no_conn_total 68254
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197011
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1318
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 872
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 673
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6345
telemt_me_writer_restored_same_endpoint_total 6263
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 196808
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 2712841348 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 88922693256 (82.82 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 39455.1 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126904
telemt_connections_bad_total 2195
telemt_handshake_timeouts_total 10205
telemt_upstream_connect_attempt_total 10914
telemt_upstream_connect_success_total 10774
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 10914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_reconnect_attempts_total 10004
telemt_me_reconnect_success_total 8830
telemt_me_reader_eof_total 9334
telemt_me_idle_close_by_peer_total 9334
telemt_me_route_drop_no_conn_total 48647
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109789
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 309
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8949
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8814
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 109801
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 1395073272 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 47154347084 (43.92 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 39231.7 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76112
telemt_connections_bad_total 1091
telemt_handshake_timeouts_total 2565
telemt_upstream_connect_attempt_total 10569
telemt_upstream_connect_success_total 10514
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8588
telemt_me_reconnect_success_total 8542
telemt_me_reader_eof_total 9137
telemt_me_idle_close_by_peer_total 9137
telemt_me_route_drop_no_conn_total 25431
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65121
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 46
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8648
telemt_me_writer_restored_same_endpoint_total 8531
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 65105
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 5972395220 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 21587891704 (20.11 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 39290.4 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127949
telemt_connections_bad_total 3723
telemt_handshake_timeouts_total 3945
telemt_upstream_connect_attempt_total 8910
telemt_upstream_connect_success_total 8834
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 6878
telemt_me_reconnect_success_total 6825
telemt_me_reader_eof_total 7271
telemt_me_idle_close_by_peer_total 7271
telemt_me_route_drop_no_conn_total 43136
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116471
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 224
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6926
telemt_me_writer_restored_same_endpoint_total 6818
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 116488
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 1280366198 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 55852260597 (52.02 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 39262.4 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98208
telemt_connections_bad_total 27749
telemt_handshake_timeouts_total 1947
telemt_upstream_connect_attempt_total 11710
telemt_upstream_connect_success_total 11555
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 11710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 11749
telemt_me_reconnect_success_total 9488
telemt_me_reader_eof_total 10016
telemt_me_idle_close_by_peer_total 10016
telemt_me_route_drop_no_conn_total 25833
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65915
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9683
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9480
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 66013
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 731675063 (697.78 MB)
telemt_user_octets_to_client{user="hello"} 28608116606 (26.64 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 39423.3 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237393
telemt_connections_bad_total 29609
telemt_handshake_timeouts_total 1773
telemt_upstream_connect_attempt_total 8074
telemt_upstream_connect_success_total 8032
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 8074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6108
telemt_me_reconnect_success_total 6081
telemt_me_reader_eof_total 6524
telemt_me_idle_close_by_peer_total 6524
telemt_me_route_drop_no_conn_total 202033
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275436
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6171
telemt_me_writer_restored_same_endpoint_total 6071
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 197688
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 3062315872 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 147762173088 (137.61 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 27429.9 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 589
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 13655
telemt_upstream_connect_success_total 13655
telemt_upstream_connect_attempts_per_request{bucket="1"} 13655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 12287
telemt_me_reconnect_success_total 12220
telemt_me_reader_eof_total 13428
telemt_me_idle_close_by_peer_total 13428
telemt_me_route_drop_no_conn_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 12334
telemt_me_writer_restored_same_endpoint_total 12220
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 393
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 165913268 (158.23 MB)
telemt_user_octets_to_client{user="hello"} 1266670364 (1.18 GB)
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```