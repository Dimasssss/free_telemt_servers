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

# Server Metrics 2026-03-17 13:53:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 68875.7 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 700871
telemt_connections_bad_total 5666
telemt_handshake_timeouts_total 20585
telemt_upstream_connect_attempt_total 16903
telemt_upstream_connect_success_total 16449
telemt_upstream_connect_fail_total 454
telemt_upstream_connect_attempts_per_request{bucket="1"} 16903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 454
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 18619
telemt_me_reconnect_success_total 10710
telemt_me_reader_eof_total 11512
telemt_me_idle_close_by_peer_total 11511
telemt_me_route_drop_no_conn_total 252737
telemt_me_route_drop_channel_closed_total 71
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 635671
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4549
telemt_desync_full_logged_total 1266
telemt_desync_suppressed_total 3283
telemt_desync_frames_bucket_total{bucket="1_2"} 1282
telemt_desync_frames_bucket_total{bucket="3_10"} 1868
telemt_desync_frames_bucket_total{bucket="gt_10"} 1399
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11109
telemt_me_refill_failed_total 242
telemt_me_writer_restored_same_endpoint_total 10688
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 637559
telemt_user_connections_current{user="hello"} 903
telemt_user_octets_from_client{user="hello"} 10263509643 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 220215731679 (205.09 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 69133.3 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433065
telemt_connections_bad_total 26554
telemt_handshake_timeouts_total 21811
telemt_upstream_connect_attempt_total 25050
telemt_upstream_connect_success_total 24732
telemt_upstream_connect_fail_total 313
telemt_upstream_connect_attempts_per_request{bucket="1"} 25045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 313
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 30408
telemt_me_reconnect_success_total 13320
telemt_me_reader_eof_total 14422
telemt_me_idle_close_by_peer_total 14422
telemt_me_route_drop_no_conn_total 184551
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355073
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1419
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 971
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 620
telemt_desync_frames_bucket_total{bucket="gt_10"} 486
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14017
telemt_me_refill_failed_total 530
telemt_me_writer_restored_same_endpoint_total 13304
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 697
telemt_user_connections_total{user="hello"} 362949
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 3905252996 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 118761183488 (110.60 GB)
telemt_user_msgs_from_client{user="hello"} 99885
telemt_user_msgs_to_client{user="hello"} 275819
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 68903.1 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229981
telemt_connections_bad_total 7806
telemt_handshake_timeouts_total 16732
telemt_upstream_connect_attempt_total 18254
telemt_upstream_connect_success_total 18162
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 18254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 20262
telemt_me_reconnect_success_total 14669
telemt_me_reader_eof_total 15718
telemt_me_idle_close_by_peer_total 15718
telemt_me_route_drop_no_conn_total 86619
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193375
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 743
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 274
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15050
telemt_me_refill_failed_total 172
telemt_me_writer_restored_same_endpoint_total 14658
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 193256
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 15332599456 (14.28 GB)
telemt_user_octets_to_client{user="hello"} 52485198332 (48.88 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 68962.6 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525959
telemt_connections_bad_total 8079
telemt_handshake_timeouts_total 12853
telemt_upstream_connect_attempt_total 16384
telemt_upstream_connect_success_total 16234
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 16384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 19727
telemt_me_reconnect_success_total 11732
telemt_me_reader_eof_total 12643
telemt_me_idle_close_by_peer_total 12643
telemt_me_route_drop_no_conn_total 159845
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447507
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1581
telemt_desync_full_logged_total 547
telemt_desync_suppressed_total 1034
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12187
telemt_me_refill_failed_total 245
telemt_me_writer_restored_same_endpoint_total 11723
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 448380
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 5634222558 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 151055825187 (140.68 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 68949.5 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260374
telemt_connections_bad_total 56450
telemt_handshake_timeouts_total 3293
telemt_upstream_connect_attempt_total 20132
telemt_upstream_connect_success_total 19681
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 20132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 273
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 35838
telemt_me_reconnect_success_total 15826
telemt_me_reader_eof_total 17029
telemt_me_idle_close_by_peer_total 17027
telemt_me_route_drop_no_conn_total 69860
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190259
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1092
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 864
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16710
telemt_me_refill_failed_total 621
telemt_me_writer_restored_same_endpoint_total 15818
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 884
telemt_user_connections_total{user="hello"} 190701
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 2531010356 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 71762752627 (66.83 GB)
telemt_user_msgs_from_client{user="hello"} 1000
telemt_user_msgs_to_client{user="hello"} 2255
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 69096.6 (19h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624225
telemt_connections_bad_total 53474
telemt_handshake_timeouts_total 6142
telemt_upstream_connect_attempt_total 13950
telemt_upstream_connect_success_total 13875
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 13950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 18079
telemt_me_reconnect_success_total 10424
telemt_me_reader_eof_total 11304
telemt_me_idle_close_by_peer_total 11304
telemt_me_route_drop_no_conn_total 433216
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 627889
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 842
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 532
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10822
telemt_me_refill_failed_total 237
telemt_me_writer_restored_same_endpoint_total 10410
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 532373
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 8089842356 (7.53 GB)
telemt_user_octets_to_client{user="hello"} 248770748696 (231.69 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 16862.5 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13392
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 9562
telemt_upstream_connect_success_total 9486
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 16210
telemt_me_reconnect_success_total 8475
telemt_me_reader_eof_total 8915
telemt_me_idle_close_by_peer_total 8915
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 4541
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12953
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 8800
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 8460
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 13054
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 365129233 (348.21 MB)
telemt_user_octets_to_client{user="hello"} 22107012166 (20.59 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```