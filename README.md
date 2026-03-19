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

# Server Metrics 2026-03-19 02:28:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 16816.9 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204927
telemt_connections_bad_total 24679
telemt_connections_current 671
telemt_connections_me_current 671
telemt_handshake_timeouts_total 12169
telemt_upstream_connect_attempt_total 3358
telemt_upstream_connect_success_total 3304
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 3358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2467
telemt_me_reconnect_success_total 2456
telemt_me_reader_eof_total 2568
telemt_me_idle_close_by_peer_total 2568
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 56359
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159070
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1091
telemt_desync_full_logged_total 291
telemt_desync_suppressed_total 800
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 468
telemt_desync_frames_bucket_total{bucket="gt_10"} 223
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2467
telemt_me_writer_restored_same_endpoint_total 2441
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 156297
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 1687959596 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 50380650420 (46.92 GB)
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 16820.2 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367215
telemt_connections_bad_total 23200
telemt_connections_current 1494
telemt_connections_me_current 1494
telemt_handshake_timeouts_total 8602
telemt_upstream_connect_attempt_total 3260
telemt_upstream_connect_success_total 3203
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 3260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 2357
telemt_me_reconnect_success_total 2347
telemt_me_reader_eof_total 2471
telemt_me_idle_close_by_peer_total 2471
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 112732
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313938
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1159
telemt_desync_full_logged_total 384
telemt_desync_suppressed_total 775
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 453
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2385
telemt_me_writer_restored_same_endpoint_total 2332
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 313976
telemt_user_connections_current{user="hello"} 1494
telemt_user_octets_from_client{user="hello"} 11761252212 (10.95 GB)
telemt_user_octets_to_client{user="hello"} 121633695640 (113.28 GB)
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 16817.5 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298867
telemt_connections_bad_total 56777
telemt_connections_current 1202
telemt_connections_me_current 1202
telemt_handshake_timeouts_total 7047
telemt_upstream_connect_attempt_total 3243
telemt_upstream_connect_success_total 3243
telemt_upstream_connect_attempts_per_request{bucket="1"} 3243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1602
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2396
telemt_me_reconnect_success_total 2388
telemt_me_reader_eof_total 2523
telemt_me_idle_close_by_peer_total 2523
telemt_me_route_drop_no_conn_total 90247
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226567
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1159
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 732
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 484
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2425
telemt_me_writer_restored_same_endpoint_total 2372
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 226553
telemt_user_connections_current{user="hello"} 1202
telemt_user_octets_from_client{user="hello"} 3485136676 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 132025682660 (122.96 GB)
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 16870.7 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351720
telemt_connections_bad_total 34237
telemt_connections_current 968
telemt_connections_me_current 968
telemt_handshake_timeouts_total 5393
telemt_upstream_connect_attempt_total 3087
telemt_upstream_connect_success_total 3087
telemt_upstream_connect_attempts_per_request{bucket="1"} 3087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2243
telemt_me_reconnect_success_total 2232
telemt_me_reader_eof_total 2348
telemt_me_idle_close_by_peer_total 2348
telemt_me_route_drop_no_conn_total 102027
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227081
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 578
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 363
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2261
telemt_me_writer_restored_same_endpoint_total 2208
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 226992
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 2054557892 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 77539711976 (72.21 GB)
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 16814.1 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321065
telemt_connections_bad_total 18434
telemt_connections_current 1301
telemt_connections_me_current 1301
telemt_handshake_timeouts_total 10850
telemt_upstream_connect_attempt_total 3201
telemt_upstream_connect_success_total 3183
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2340
telemt_me_reconnect_success_total 2326
telemt_me_reader_eof_total 2451
telemt_me_idle_close_by_peer_total 2451
telemt_me_route_drop_no_conn_total 97478
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247665
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1031
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 641
telemt_desync_frames_bucket_total{bucket="1_2"} 280
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2339
telemt_me_writer_restored_same_endpoint_total 2302
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 247587
telemt_user_connections_current{user="hello"} 1301
telemt_user_octets_from_client{user="hello"} 8282317608 (7.71 GB)
telemt_user_octets_to_client{user="hello"} 135910824240 (126.58 GB)
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 16825.5 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80108
telemt_connections_bad_total 9335
telemt_connections_current 346
telemt_connections_me_current 346
telemt_handshake_timeouts_total 344
telemt_upstream_connect_attempt_total 4893
telemt_upstream_connect_success_total 4751
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 4893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 5736
telemt_me_reconnect_success_total 3902
telemt_me_reader_eof_total 4085
telemt_me_idle_close_by_peer_total 4085
telemt_me_route_drop_no_conn_total 31822
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67872
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 34
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3956
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3872
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 67871
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 1523444420 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 50343925520 (46.89 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 16816.5 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226930
telemt_connections_bad_total 23958
telemt_connections_current 1093
telemt_connections_me_current 1093
telemt_handshake_timeouts_total 11185
telemt_upstream_connect_attempt_total 3609
telemt_upstream_connect_success_total 3609
telemt_upstream_connect_attempts_per_request{bucket="1"} 3609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2765
telemt_me_reconnect_success_total 2756
telemt_me_reader_eof_total 2899
telemt_me_idle_close_by_peer_total 2899
telemt_me_route_drop_no_conn_total 66856
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186374
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1072
telemt_desync_full_logged_total 416
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2788
telemt_me_writer_restored_same_endpoint_total 2741
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 186398
telemt_user_connections_current{user="hello"} 1093
telemt_user_octets_from_client{user="hello"} 1943026676 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 95704122536 (89.13 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 100
```