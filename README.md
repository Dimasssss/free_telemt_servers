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

# Server Metrics 2026-03-17 02:04:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 26367.8 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142590
telemt_connections_bad_total 2232
telemt_handshake_timeouts_total 5276
telemt_upstream_connect_attempt_total 5601
telemt_upstream_connect_success_total 5564
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 5601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4241
telemt_me_reconnect_success_total 4227
telemt_me_reader_eof_total 4488
telemt_me_idle_close_by_peer_total 4488
telemt_me_route_drop_no_conn_total 43857
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129077
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 707
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4261
telemt_me_writer_restored_same_endpoint_total 4206
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 129010
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 1812300516 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 60015237152 (55.89 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 26619.1 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81854
telemt_connections_bad_total 1238
telemt_handshake_timeouts_total 2918
telemt_upstream_connect_attempt_total 6839
telemt_upstream_connect_success_total 6748
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 6839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_reconnect_attempts_total 5432
telemt_me_reconnect_success_total 5419
telemt_me_reader_eof_total 5696
telemt_me_idle_close_by_peer_total 5696
telemt_me_route_drop_no_conn_total 34092
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74333
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 174
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5475
telemt_me_writer_restored_same_endpoint_total 5403
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 74276
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 1119453928 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 35059981508 (32.65 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 26395.2 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52373
telemt_connections_bad_total 564
telemt_handshake_timeouts_total 1847
telemt_upstream_connect_attempt_total 7202
telemt_upstream_connect_success_total 7159
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 5842
telemt_me_reconnect_success_total 5809
telemt_me_reader_eof_total 6211
telemt_me_idle_close_by_peer_total 6211
telemt_me_route_drop_no_conn_total 16291
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44148
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5885
telemt_me_writer_restored_same_endpoint_total 5798
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 44133
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 5531831128 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 16800594488 (15.65 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 26454.6 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81418
telemt_connections_bad_total 3085
telemt_handshake_timeouts_total 482
telemt_upstream_connect_attempt_total 6212
telemt_upstream_connect_success_total 6155
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 6212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 4840
telemt_me_reconnect_success_total 4807
telemt_me_reader_eof_total 5097
telemt_me_idle_close_by_peer_total 5097
telemt_me_route_drop_no_conn_total 28004
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75587
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4873
telemt_me_writer_restored_same_endpoint_total 4800
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 75571
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 900113200 (858.41 MB)
telemt_user_octets_to_client{user="hello"} 35874091668 (33.41 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 26426.7 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61748
telemt_connections_bad_total 15407
telemt_handshake_timeouts_total 330
telemt_upstream_connect_attempt_total 7953
telemt_upstream_connect_success_total 7850
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 7953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_reconnect_attempts_total 8751
telemt_me_reconnect_success_total 6506
telemt_me_reader_eof_total 6853
telemt_me_idle_close_by_peer_total 6853
telemt_me_route_drop_no_conn_total 17618
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44199
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 6679
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 6498
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 44194
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 464822700 (443.29 MB)
telemt_user_octets_to_client{user="hello"} 14241143352 (13.26 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 26587.8 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151143
telemt_connections_bad_total 4596
telemt_handshake_timeouts_total 1041
telemt_upstream_connect_attempt_total 5486
telemt_upstream_connect_success_total 5454
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2869
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 4135
telemt_me_reconnect_success_total 4122
telemt_me_reader_eof_total 4414
telemt_me_idle_close_by_peer_total 4414
telemt_me_route_drop_no_conn_total 173161
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218035
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4179
telemt_me_writer_restored_same_endpoint_total 4112
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 140290
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 2312266896 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 114961247456 (107.07 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 14594.2 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 7367
telemt_upstream_connect_success_total 7367
telemt_upstream_connect_attempts_per_request{bucket="1"} 7367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6605
telemt_me_reconnect_success_total 6564
telemt_me_reader_eof_total 7204
telemt_me_idle_close_by_peer_total 7204
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6632
telemt_me_writer_restored_same_endpoint_total 6564
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```