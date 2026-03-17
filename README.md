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

# Server Metrics 2026-03-17 13:37:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 67958.4 (18h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679169
telemt_connections_bad_total 5353
telemt_handshake_timeouts_total 20396
telemt_upstream_connect_attempt_total 16752
telemt_upstream_connect_success_total 16299
telemt_upstream_connect_fail_total 453
telemt_upstream_connect_attempts_per_request{bucket="1"} 16752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 453
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 17139
telemt_me_reconnect_success_total 10606
telemt_me_reader_eof_total 11366
telemt_me_idle_close_by_peer_total 11365
telemt_me_route_drop_no_conn_total 231736
telemt_me_route_drop_channel_closed_total 69
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 615191
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4474
telemt_desync_full_logged_total 1239
telemt_desync_suppressed_total 3235
telemt_desync_frames_bucket_total{bucket="1_2"} 1275
telemt_desync_frames_bucket_total{bucket="3_10"} 1839
telemt_desync_frames_bucket_total{bucket="gt_10"} 1360
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10962
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 10584
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 617080
telemt_user_connections_current{user="hello"} 1048
telemt_user_octets_from_client{user="hello"} 9844885627 (9.17 GB)
telemt_user_octets_to_client{user="hello"} 217417051219 (202.49 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 333
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 68210.0 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417623
telemt_connections_bad_total 24908
telemt_handshake_timeouts_total 21230
telemt_upstream_connect_attempt_total 17953
telemt_upstream_connect_success_total 17670
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 17953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 458
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 28989
telemt_me_reconnect_success_total 13278
telemt_me_reader_eof_total 14341
telemt_me_idle_close_by_peer_total 14341
telemt_me_route_drop_no_conn_total 179635
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349220
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1396
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 952
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 477
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13932
telemt_me_refill_failed_total 487
telemt_me_writer_restored_same_endpoint_total 13262
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 654
telemt_user_connections_total{user="hello"} 350125
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 3782652247 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 117222069759 (109.17 GB)
telemt_user_msgs_from_client{user="hello"} 2850
telemt_user_msgs_to_client{user="hello"} 6435
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 67985.8 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223927
telemt_connections_bad_total 7796
telemt_handshake_timeouts_total 16667
telemt_upstream_connect_attempt_total 18006
telemt_upstream_connect_success_total 17916
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 18006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9874
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 18878
telemt_me_reconnect_success_total 14469
telemt_me_reader_eof_total 15481
telemt_me_idle_close_by_peer_total 15481
telemt_me_route_drop_no_conn_total 82095
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187831
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 730
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 319
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14811
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 14458
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 187716
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 15276556584 (14.23 GB)
telemt_user_octets_to_client{user="hello"} 51710492176 (48.16 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 68045.1 (18h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510853
telemt_connections_bad_total 7943
telemt_handshake_timeouts_total 12769
telemt_upstream_connect_attempt_total 16263
telemt_upstream_connect_success_total 16116
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 16263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 18313
telemt_me_reconnect_success_total 11664
telemt_me_reader_eof_total 12535
telemt_me_idle_close_by_peer_total 12535
telemt_me_route_drop_no_conn_total 150738
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433258
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1538
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1006
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 691
telemt_desync_frames_bucket_total{bucket="gt_10"} 473
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12077
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 11655
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 434139
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 5511008998 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 147269589967 (137.16 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 68017.0 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253905
telemt_connections_bad_total 56288
telemt_handshake_timeouts_total 3253
telemt_upstream_connect_attempt_total 19511
telemt_upstream_connect_success_total 19255
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 19511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 34308
telemt_me_reconnect_success_total 15716
telemt_me_reader_eof_total 16931
telemt_me_idle_close_by_peer_total 16931
telemt_me_route_drop_no_conn_total 67263
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184837
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
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
telemt_me_writer_removed_unexpected_total 16502
telemt_me_refill_failed_total 578
telemt_me_writer_restored_same_endpoint_total 15708
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 786
telemt_user_connections_total{user="hello"} 184974
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 2477793267 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 70968927050 (66.09 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 68179.1 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608200
telemt_connections_bad_total 53259
telemt_handshake_timeouts_total 6027
telemt_upstream_connect_attempt_total 13810
telemt_upstream_connect_success_total 13737
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 13810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 16644
telemt_me_reconnect_success_total 10333
telemt_me_reader_eof_total 11171
telemt_me_idle_close_by_peer_total 11171
telemt_me_route_drop_no_conn_total 413760
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 610613
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 838
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10689
telemt_me_refill_failed_total 195
telemt_me_writer_restored_same_endpoint_total 10319
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 517538
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 7679743320 (7.15 GB)
telemt_user_octets_to_client{user="hello"} 244986096596 (228.16 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 15945.1 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12470
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 9042
telemt_upstream_connect_success_total 8970
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 9042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 14618
telemt_me_reconnect_success_total 8004
telemt_me_reader_eof_total 8404
telemt_me_idle_close_by_peer_total 8404
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 4287
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12054
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 8287
telemt_me_refill_failed_total 205
telemt_me_writer_restored_same_endpoint_total 7990
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 12155
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 348715149 (332.56 MB)
telemt_user_octets_to_client{user="hello"} 21828351998 (20.33 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 11
```