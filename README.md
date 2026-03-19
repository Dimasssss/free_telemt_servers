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

# Server Metrics 2026-03-19 07:30:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 34907.1 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 607684
telemt_connections_bad_total 62832
telemt_connections_current 1395
telemt_connections_me_current 1395
telemt_handshake_timeouts_total 23785
telemt_upstream_connect_attempt_total 6717
telemt_upstream_connect_success_total 6593
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 6717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 6003
telemt_me_reconnect_success_total 4853
telemt_me_reader_eof_total 5152
telemt_me_idle_close_by_peer_total 5151
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 171630
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457307
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3117
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 2239
telemt_desync_frames_bucket_total{bucket="1_2"} 1097
telemt_desync_frames_bucket_total{bucket="3_10"} 1172
telemt_desync_frames_bucket_total{bucket="gt_10"} 848
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4943
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4836
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 454425
telemt_user_connections_current{user="hello"} 1395
telemt_user_octets_from_client{user="hello"} 6053468012 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 152576921912 (142.10 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 34911.0 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1427588
telemt_connections_bad_total 80376
telemt_connections_current 3967
telemt_connections_me_current 3967
telemt_handshake_timeouts_total 34002
telemt_upstream_connect_attempt_total 6532
telemt_upstream_connect_success_total 6407
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 6532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 5809
telemt_me_reconnect_success_total 4655
telemt_me_reader_eof_total 4946
telemt_me_idle_close_by_peer_total 4946
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 596981
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1170786
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5192
telemt_desync_full_logged_total 1741
telemt_desync_suppressed_total 3451
telemt_desync_frames_bucket_total{bucket="1_2"} 934
telemt_desync_frames_bucket_total{bucket="3_10"} 1956
telemt_desync_frames_bucket_total{bucket="gt_10"} 2302
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4779
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4634
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 1170709
telemt_user_connections_current{user="hello"} 3967
telemt_user_octets_from_client{user="hello"} 21732570260 (20.24 GB)
telemt_user_octets_to_client{user="hello"} 470374217652 (438.07 GB)
telemt_user_unique_ips_current{user="hello"} 1341
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 34909.1 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1211550
telemt_connections_bad_total 173441
telemt_connections_current 3278
telemt_connections_me_current 3278
telemt_handshake_timeouts_total 32965
telemt_upstream_connect_attempt_total 6260
telemt_upstream_connect_success_total 6260
telemt_upstream_connect_attempts_per_request{bucket="1"} 6260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 4534
telemt_me_reconnect_success_total 4510
telemt_me_reader_eof_total 4778
telemt_me_idle_close_by_peer_total 4778
telemt_me_route_drop_no_conn_total 519949
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 909920
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4240
telemt_desync_full_logged_total 1322
telemt_desync_suppressed_total 2918
telemt_desync_frames_bucket_total{bucket="1_2"} 848
telemt_desync_frames_bucket_total{bucket="3_10"} 1511
telemt_desync_frames_bucket_total{bucket="gt_10"} 1881
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4594
telemt_me_writer_restored_same_endpoint_total 4494
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 909547
telemt_user_connections_current{user="hello"} 3278
telemt_user_octets_from_client{user="hello"} 16196334132 (15.08 GB)
telemt_user_octets_to_client{user="hello"} 461336196428 (429.65 GB)
telemt_user_unique_ips_current{user="hello"} 1071
telemt_user_unique_ips_recent_window{user="hello"} 486
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 34961.8 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1263861
telemt_connections_bad_total 89631
telemt_connections_current 3152
telemt_connections_me_current 3152
telemt_handshake_timeouts_total 31128
telemt_upstream_connect_attempt_total 6072
telemt_upstream_connect_success_total 6072
telemt_upstream_connect_attempts_per_request{bucket="1"} 6072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5372
telemt_me_reconnect_success_total 4311
telemt_me_reader_eof_total 4584
telemt_me_idle_close_by_peer_total 4583
telemt_me_route_drop_no_conn_total 459071
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 863152
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3251
telemt_desync_full_logged_total 1135
telemt_desync_suppressed_total 2116
telemt_desync_frames_bucket_total{bucket="1_2"} 612
telemt_desync_frames_bucket_total{bucket="3_10"} 1277
telemt_desync_frames_bucket_total{bucket="gt_10"} 1362
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4406
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4287
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 861973
telemt_user_connections_current{user="hello"} 3152
telemt_user_octets_from_client{user="hello"} 12347367896 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 303567605528 (282.72 GB)
telemt_user_unique_ips_current{user="hello"} 1011
telemt_user_unique_ips_recent_window{user="hello"} 490
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 34904.8 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1518567
telemt_connections_bad_total 416973
telemt_connections_current 3304
telemt_connections_me_current 3304
telemt_handshake_timeouts_total 32838
telemt_upstream_connect_attempt_total 6112
telemt_upstream_connect_success_total 6075
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 4361
telemt_me_reconnect_success_total 4329
telemt_me_reader_eof_total 4588
telemt_me_idle_close_by_peer_total 4588
telemt_me_route_drop_no_conn_total 378993
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 911255
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4451
telemt_desync_full_logged_total 1390
telemt_desync_suppressed_total 3061
telemt_desync_frames_bucket_total{bucket="1_2"} 990
telemt_desync_frames_bucket_total{bucket="3_10"} 2008
telemt_desync_frames_bucket_total{bucket="gt_10"} 1453
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4385
telemt_me_writer_restored_same_endpoint_total 4305
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 910949
telemt_user_connections_current{user="hello"} 3304
telemt_user_octets_from_client{user="hello"} 19667755588 (18.32 GB)
telemt_user_octets_to_client{user="hello"} 448469716612 (417.67 GB)
telemt_user_unique_ips_current{user="hello"} 1139
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 34916.8 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254705
telemt_connections_bad_total 13063
telemt_connections_current 859
telemt_connections_me_current 859
telemt_handshake_timeouts_total 2214
telemt_upstream_connect_attempt_total 9140
telemt_upstream_connect_success_total 8906
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 9140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 12531
telemt_me_reconnect_success_total 7157
telemt_me_reader_eof_total 7603
telemt_me_idle_close_by_peer_total 7603
telemt_me_route_drop_no_conn_total 119874
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226358
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 354
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 7367
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7127
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 226332
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 3447269048 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 111735744448 (104.06 GB)
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 34907.5 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958320
telemt_connections_bad_total 90969
telemt_connections_current 2987
telemt_connections_me_current 2987
telemt_handshake_timeouts_total 41464
telemt_upstream_connect_attempt_total 7110
telemt_upstream_connect_success_total 7110
telemt_upstream_connect_attempts_per_request{bucket="1"} 7110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6697
telemt_me_reconnect_success_total 5364
telemt_me_reader_eof_total 5694
telemt_me_idle_close_by_peer_total 5694
telemt_me_route_drop_no_conn_total 386617
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 789457
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4642
telemt_desync_full_logged_total 1546
telemt_desync_suppressed_total 3096
telemt_desync_frames_bucket_total{bucket="1_2"} 912
telemt_desync_frames_bucket_total{bucket="3_10"} 1785
telemt_desync_frames_bucket_total{bucket="gt_10"} 1945
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5463
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5349
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 788542
telemt_user_connections_current{user="hello"} 2987
telemt_user_octets_from_client{user="hello"} 11593511844 (10.80 GB)
telemt_user_octets_to_client{user="hello"} 433612731748 (403.83 GB)
telemt_user_unique_ips_current{user="hello"} 952
telemt_user_unique_ips_recent_window{user="hello"} 388
```