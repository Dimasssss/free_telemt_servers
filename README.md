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

# Server Metrics 2026-03-19 13:54:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 1111.5 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74277
telemt_connections_bad_total 35
telemt_connections_current 140
telemt_connections_me_current 140
telemt_handshake_timeouts_total 66031
telemt_upstream_connect_attempt_total 641
telemt_upstream_connect_success_total 637
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 328
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 463
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 386
telemt_me_idle_close_by_peer_total 386
telemt_me_route_drop_no_conn_total 1900
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3021
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 63
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_close_signal_drop_total 18
telemt_me_writer_removed_unexpected_total 404
telemt_me_writer_restored_same_endpoint_total 438
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 10
telemt_me_async_recovery_trigger_total 102
telemt_user_connections_total{user="hello"} 2754
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 34918543 (33.30 MB)
telemt_user_octets_to_client{user="hello"} 854733968 (815.14 MB)
telemt_user_msgs_from_client{user="hello"} 261
telemt_user_msgs_to_client{user="hello"} 430
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 4247.4 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456075
telemt_connections_bad_total 12529
telemt_connections_current 3543
telemt_connections_me_current 3543
telemt_handshake_timeouts_total 7102
telemt_upstream_connect_attempt_total 2203
telemt_upstream_connect_success_total 2191
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 3576
telemt_me_reconnect_success_total 721
telemt_me_reader_eof_total 764
telemt_me_idle_close_by_peer_total 764
telemt_me_route_drop_no_conn_total 411674
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409079
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1270
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 855
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 479
telemt_desync_frames_bucket_total{bucket="gt_10"} 559
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 792
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 666
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 409929
telemt_user_connections_current{user="hello"} 3543
telemt_user_octets_from_client{user="hello"} 5809289906 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 101185889870 (94.24 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1281
telemt_user_unique_ips_recent_window{user="hello"} 585
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 4225.7 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516868
telemt_connections_bad_total 47937
telemt_connections_current 3013
telemt_connections_me_current 3013
telemt_handshake_timeouts_total 5260
telemt_upstream_connect_attempt_total 673
telemt_upstream_connect_success_total 667
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1317
telemt_me_reconnect_success_total 419
telemt_me_reader_eof_total 351
telemt_me_idle_close_by_peer_total 350
telemt_me_route_drop_no_conn_total 505141
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385835
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1327
telemt_desync_full_logged_total 335
telemt_desync_suppressed_total 992
telemt_desync_frames_bucket_total{bucket="1_2"} 359
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 467
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 27
telemt_me_writer_removed_unexpected_total 372
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 418
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 383664
telemt_user_connections_current{user="hello"} 3013
telemt_user_octets_from_client{user="hello"} 3179122072 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 90107089836 (83.92 GB)
telemt_user_unique_ips_current{user="hello"} 1046
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 4213.4 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373841
telemt_connections_bad_total 37979
telemt_connections_current 2856
telemt_connections_me_current 2856
telemt_handshake_timeouts_total 6203
telemt_upstream_connect_attempt_total 4192
telemt_upstream_connect_success_total 4034
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 4192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 484
telemt_me_reconnect_success_total 461
telemt_me_reader_eof_total 435
telemt_me_idle_close_by_peer_total 434
telemt_me_route_drop_no_conn_total 220841
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298106
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1186
telemt_desync_full_logged_total 399
telemt_desync_suppressed_total 787
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 427
telemt_desync_frames_bucket_total{bucket="gt_10"} 535
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 454
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 301229
telemt_user_connections_current{user="hello"} 2856
telemt_user_octets_from_client{user="hello"} 3824374631 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 69933031942 (65.13 GB)
telemt_user_msgs_from_client{user="hello"} 5613
telemt_user_msgs_to_client{user="hello"} 6373
telemt_user_unique_ips_current{user="hello"} 984
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 57936.4 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3967201
telemt_connections_bad_total 760767
telemt_connections_current 3348
telemt_connections_me_current 3348
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 78255
telemt_upstream_connect_attempt_total 62140
telemt_upstream_connect_success_total 59657
telemt_upstream_connect_fail_total 2483
telemt_upstream_connect_attempts_per_request{bucket="1"} 62140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1016
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2483
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70623
telemt_me_reconnect_success_total 7563
telemt_me_reader_eof_total 7901
telemt_me_idle_close_by_peer_total 7898
telemt_me_route_drop_no_conn_total 1893427
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2699718
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
telemt_desync_total 11635
telemt_desync_full_logged_total 3584
telemt_desync_suppressed_total 8051
telemt_desync_frames_bucket_total{bucket="1_2"} 2032
telemt_desync_frames_bucket_total{bucket="3_10"} 5002
telemt_desync_frames_bucket_total{bucket="gt_10"} 4601
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7696
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7539
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 2748434
telemt_user_connections_current{user="hello"} 3348
telemt_user_octets_from_client{user="hello"} 44460633735 (41.41 GB)
telemt_user_octets_to_client{user="hello"} 982455645524 (914.98 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1127
telemt_user_unique_ips_recent_window{user="hello"} 501
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 4178.7 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106761
telemt_connections_bad_total 5097
telemt_connections_current 935
telemt_connections_me_current 935
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 4759
telemt_upstream_connect_attempt_total 3368
telemt_upstream_connect_success_total 3232
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 3368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 471
telemt_me_reconnect_success_total 453
telemt_me_reader_eof_total 404
telemt_me_idle_close_by_peer_total 404
telemt_me_route_drop_no_conn_total 83755
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89925
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 185
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_restored_same_endpoint_total 444
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 92567
telemt_user_connections_current{user="hello"} 935
telemt_user_octets_from_client{user="hello"} 1278464216 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 21211827718 (19.76 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 4177.9 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289752
telemt_connections_bad_total 23639
telemt_connections_current 3023
telemt_connections_me_current 3023
telemt_handshake_timeouts_total 5142
telemt_upstream_connect_attempt_total 646
telemt_upstream_connect_success_total 642
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 302
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 402
telemt_me_reconnect_success_total 396
telemt_me_reader_eof_total 401
telemt_me_idle_close_by_peer_total 401
telemt_me_route_drop_no_conn_total 86535
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251707
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1134
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 793
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 401
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 406
telemt_me_writer_restored_same_endpoint_total 379
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 251627
telemt_user_connections_current{user="hello"} 3023
telemt_user_octets_from_client{user="hello"} 3021557380 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 105501466188 (98.26 GB)
telemt_user_unique_ips_current{user="hello"} 1032
telemt_user_unique_ips_recent_window{user="hello"} 430
```