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

# Server Metrics 2026-03-17 16:31:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 78390.2 (21h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 909316
telemt_connections_bad_total 6474
telemt_handshake_timeouts_total 25549
telemt_upstream_connect_attempt_total 18705
telemt_upstream_connect_success_total 18233
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 18705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29094
telemt_me_reconnect_success_total 11981
telemt_me_reader_eof_total 13072
telemt_me_idle_close_by_peer_total 13071
telemt_me_route_drop_no_conn_total 419491
telemt_me_route_drop_channel_closed_total 106
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 835734
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5592
telemt_desync_full_logged_total 1559
telemt_desync_suppressed_total 4033
telemt_desync_frames_bucket_total{bucket="1_2"} 1595
telemt_desync_frames_bucket_total{bucket="3_10"} 2171
telemt_desync_frames_bucket_total{bucket="gt_10"} 1826
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12680
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 11959
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 699
telemt_user_connections_total{user="hello"} 830153
telemt_user_connections_current{user="hello"} 1280
telemt_user_octets_from_client{user="hello"} 12958409267 (12.07 GB)
telemt_user_octets_to_client{user="hello"} 275686320755 (256.75 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 78643.2 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634777
telemt_connections_bad_total 37133
telemt_handshake_timeouts_total 29061
telemt_upstream_connect_attempt_total 174550
telemt_upstream_connect_success_total 173939
telemt_upstream_connect_fail_total 605
telemt_upstream_connect_attempts_per_request{bucket="1"} 174544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 605
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 45678
telemt_me_reconnect_success_total 13539
telemt_me_reader_eof_total 15095
telemt_me_idle_close_by_peer_total 15095
telemt_me_route_drop_no_conn_total 204135
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383948
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1502
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 652
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14706
telemt_me_refill_failed_total 1000
telemt_me_writer_restored_same_endpoint_total 13523
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1167
telemt_user_connections_total{user="hello"} 540294
telemt_user_connections_current{user="hello"} 1703
telemt_user_octets_from_client{user="hello"} 6228090660 (5.80 GB)
telemt_user_octets_to_client{user="hello"} 146980177053 (136.89 GB)
telemt_user_msgs_from_client{user="hello"} 2309011
telemt_user_msgs_to_client{user="hello"} 9034957
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 78418.4 (21h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315199
telemt_connections_bad_total 9099
telemt_handshake_timeouts_total 19570
telemt_upstream_connect_attempt_total 20051
telemt_upstream_connect_success_total 19942
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 20051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 35386
telemt_me_reconnect_success_total 15930
telemt_me_reader_eof_total 17398
telemt_me_idle_close_by_peer_total 17395
telemt_me_route_drop_no_conn_total 168238
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272046
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 864
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 613
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16747
telemt_me_refill_failed_total 605
telemt_me_writer_restored_same_endpoint_total 15919
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 817
telemt_user_connections_total{user="hello"} 270239
telemt_user_connections_current{user="hello"} 1118
telemt_user_octets_from_client{user="hello"} 20848594756 (19.42 GB)
telemt_user_octets_to_client{user="hello"} 68790683572 (64.07 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 78477.0 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737682
telemt_connections_bad_total 11433
telemt_handshake_timeouts_total 15034
telemt_upstream_connect_attempt_total 79846
telemt_upstream_connect_success_total 79455
telemt_upstream_connect_fail_total 391
telemt_upstream_connect_attempts_per_request{bucket="1"} 79846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 391
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 32409
telemt_me_reconnect_success_total 12116
telemt_me_reader_eof_total 13397
telemt_me_idle_close_by_peer_total 13396
telemt_me_route_drop_no_conn_total 272309
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 577020
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1952
telemt_desync_full_logged_total 656
telemt_desync_suppressed_total 1296
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 878
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12959
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12107
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 843
telemt_user_connections_total{user="hello"} 640165
telemt_user_connections_current{user="hello"} 1592
telemt_user_octets_from_client{user="hello"} 7793715943 (7.26 GB)
telemt_user_octets_to_client{user="hello"} 192722775129 (179.49 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 78449.1 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337480
telemt_connections_bad_total 60841
telemt_handshake_timeouts_total 3919
telemt_upstream_connect_attempt_total 38060
telemt_upstream_connect_success_total 37568
telemt_upstream_connect_fail_total 492
telemt_upstream_connect_attempts_per_request{bucket="1"} 38060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 492
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48403
telemt_me_reconnect_success_total 17115
telemt_me_reader_eof_total 18683
telemt_me_idle_close_by_peer_total 18681
telemt_me_route_drop_no_conn_total 92394
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242128
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1149
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18374
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17107
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1259
telemt_user_connections_total{user="hello"} 258812
telemt_user_connections_current{user="hello"} 1256
telemt_user_octets_from_client{user="hello"} 3193960148 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 97211166552 (90.53 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 78611.1 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 779801
telemt_connections_bad_total 60202
telemt_handshake_timeouts_total 7314
telemt_upstream_connect_attempt_total 15882
telemt_upstream_connect_success_total 15796
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 15882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 23093
telemt_me_reconnect_success_total 11829
telemt_me_reader_eof_total 12883
telemt_me_idle_close_by_peer_total 12881
telemt_me_route_drop_no_conn_total 586357
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 803611
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1301
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 511
telemt_desync_frames_bucket_total{bucket="gt_10"} 490
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12374
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 11815
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 672979
telemt_user_connections_current{user="hello"} 959
telemt_user_octets_from_client{user="hello"} 9737037336 (9.07 GB)
telemt_user_octets_to_client{user="hello"} 301842171396 (281.11 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 26377.3 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31509
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 361
telemt_upstream_connect_attempt_total 13815
telemt_upstream_connect_success_total 13698
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 13815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23750
telemt_me_reconnect_success_total 12177
telemt_me_reader_eof_total 12892
telemt_me_idle_close_by_peer_total 12892
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 11989
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29253
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 12677
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12157
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 29299
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 1519444689 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 36565129250 (34.05 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 89
```