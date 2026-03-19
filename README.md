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

# Server Metrics 2026-03-19 03:40:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 21109.6 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270095
telemt_connections_bad_total 31033
telemt_connections_current 839
telemt_connections_me_current 839
telemt_handshake_timeouts_total 17878
telemt_upstream_connect_attempt_total 4183
telemt_upstream_connect_success_total 4118
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 4183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3065
telemt_me_reconnect_success_total 3050
telemt_me_reader_eof_total 3201
telemt_me_idle_close_by_peer_total 3201
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 70927
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204172
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1459
telemt_desync_full_logged_total 391
telemt_desync_suppressed_total 1068
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 606
telemt_desync_frames_bucket_total{bucket="gt_10"} 313
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3069
telemt_me_writer_restored_same_endpoint_total 3033
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 201397
telemt_user_connections_current{user="hello"} 839
telemt_user_octets_from_client{user="hello"} 2181376148 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 60563763240 (56.40 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 21113.4 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491543
telemt_connections_bad_total 38238
telemt_connections_current 2029
telemt_connections_me_current 2029
telemt_handshake_timeouts_total 13302
telemt_upstream_connect_attempt_total 4032
telemt_upstream_connect_success_total 3961
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 4032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_reconnect_attempts_total 2897
telemt_me_reconnect_success_total 2884
telemt_me_reader_eof_total 3040
telemt_me_idle_close_by_peer_total 3040
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 146048
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406026
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1528
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 1006
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2928
telemt_me_writer_restored_same_endpoint_total 2867
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 405999
telemt_user_connections_current{user="hello"} 2029
telemt_user_octets_from_client{user="hello"} 12754531008 (11.88 GB)
telemt_user_octets_to_client{user="hello"} 170495284268 (158.79 GB)
telemt_user_unique_ips_current{user="hello"} 785
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 21110.4 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401662
telemt_connections_bad_total 85500
telemt_connections_current 1545
telemt_connections_me_current 1545
telemt_handshake_timeouts_total 9910
telemt_upstream_connect_attempt_total 3998
telemt_upstream_connect_success_total 3998
telemt_upstream_connect_attempts_per_request{bucket="1"} 3998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 2935
telemt_me_reconnect_success_total 2925
telemt_me_reader_eof_total 3095
telemt_me_idle_close_by_peer_total 3095
telemt_me_route_drop_no_conn_total 118697
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293792
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1394
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 871
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 570
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2972
telemt_me_writer_restored_same_endpoint_total 2909
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 293788
telemt_user_connections_current{user="hello"} 1545
telemt_user_octets_from_client{user="hello"} 6151950140 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 182035764904 (169.53 GB)
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 21164.0 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484928
telemt_connections_bad_total 54489
telemt_connections_current 1330
telemt_connections_me_current 1330
telemt_handshake_timeouts_total 9260
telemt_upstream_connect_attempt_total 3873
telemt_upstream_connect_success_total 3873
telemt_upstream_connect_attempts_per_request{bucket="1"} 3873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2813
telemt_me_reconnect_success_total 2802
telemt_me_reader_eof_total 2952
telemt_me_idle_close_by_peer_total 2951
telemt_me_route_drop_no_conn_total 123361
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294173
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 823
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2834
telemt_me_writer_restored_same_endpoint_total 2778
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 293905
telemt_user_connections_current{user="hello"} 1330
telemt_user_octets_from_client{user="hello"} 3325614308 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 106036978520 (98.75 GB)
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 21107.2 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466151
telemt_connections_bad_total 73388
telemt_connections_current 1648
telemt_connections_me_current 1648
telemt_handshake_timeouts_total 15388
telemt_upstream_connect_attempt_total 4020
telemt_upstream_connect_success_total 3995
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 4020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 2934
telemt_me_reconnect_success_total 2917
telemt_me_reader_eof_total 3080
telemt_me_idle_close_by_peer_total 3080
telemt_me_route_drop_no_conn_total 125624
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317953
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1414
telemt_desync_full_logged_total 546
telemt_desync_suppressed_total 868
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 569
telemt_desync_frames_bucket_total{bucket="gt_10"} 474
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2941
telemt_me_writer_restored_same_endpoint_total 2893
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 317871
telemt_user_connections_current{user="hello"} 1648
telemt_user_octets_from_client{user="hello"} 10513388168 (9.79 GB)
telemt_user_octets_to_client{user="hello"} 187196294032 (174.34 GB)
telemt_user_unique_ips_current{user="hello"} 659
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 21118.7 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100257
telemt_connections_bad_total 10098
telemt_connections_current 395
telemt_connections_me_current 395
telemt_handshake_timeouts_total 443
telemt_upstream_connect_attempt_total 5950
telemt_upstream_connect_success_total 5784
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 5950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 6552
telemt_me_reconnect_success_total 4714
telemt_me_reader_eof_total 4958
telemt_me_idle_close_by_peer_total 4958
telemt_me_route_drop_no_conn_total 41507
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86364
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 4780
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4684
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 86356
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 1674242956 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 57246400152 (53.31 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 21109.5 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301224
telemt_connections_bad_total 29727
telemt_connections_current 1461
telemt_connections_me_current 1461
telemt_handshake_timeouts_total 16148
telemt_upstream_connect_attempt_total 4492
telemt_upstream_connect_success_total 4492
telemt_upstream_connect_attempts_per_request{bucket="1"} 4492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3431
telemt_me_reconnect_success_total 3422
telemt_me_reader_eof_total 3606
telemt_me_idle_close_by_peer_total 3606
telemt_me_route_drop_no_conn_total 85757
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247714
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1264
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 780
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3459
telemt_me_writer_restored_same_endpoint_total 3407
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 247735
telemt_user_connections_current{user="hello"} 1461
telemt_user_octets_from_client{user="hello"} 2659740604 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 133943637956 (124.74 GB)
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 158
```