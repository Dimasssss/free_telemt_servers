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

# Server Metrics 2026-03-17 14:39:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 71644.6 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 764125
telemt_connections_bad_total 5770
telemt_handshake_timeouts_total 22497
telemt_upstream_connect_attempt_total 17343
telemt_upstream_connect_success_total 16885
telemt_upstream_connect_fail_total 458
telemt_upstream_connect_attempts_per_request{bucket="1"} 17343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 458
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 22939
telemt_me_reconnect_success_total 10995
telemt_me_reader_eof_total 11921
telemt_me_idle_close_by_peer_total 11920
telemt_me_route_drop_no_conn_total 303975
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692638
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4793
telemt_desync_full_logged_total 1348
telemt_desync_suppressed_total 3445
telemt_desync_frames_bucket_total{bucket="1_2"} 1351
telemt_desync_frames_bucket_total{bucket="3_10"} 1940
telemt_desync_frames_bucket_total{bucket="gt_10"} 1502
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11521
telemt_me_refill_failed_total 368
telemt_me_writer_restored_same_endpoint_total 10973
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 694504
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 11622158671 (10.82 GB)
telemt_user_octets_to_client{user="hello"} 231691141787 (215.78 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 71895.9 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485735
telemt_connections_bad_total 31544
telemt_handshake_timeouts_total 24493
telemt_upstream_connect_attempt_total 61749
telemt_upstream_connect_success_total 61277
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 61749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4659
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 34518
telemt_me_reconnect_success_total 13392
telemt_me_reader_eof_total 14613
telemt_me_idle_close_by_peer_total 14613
telemt_me_route_drop_no_conn_total 189259
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362275
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1457
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 1001
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 493
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14215
telemt_me_refill_failed_total 656
telemt_me_writer_restored_same_endpoint_total 13376
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 823
telemt_user_connections_total{user="hello"} 406468
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 4356621794 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 123760477144 (115.26 GB)
telemt_user_msgs_from_client{user="hello"} 601209
telemt_user_msgs_to_client{user="hello"} 1945437
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 71671.9 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252444
telemt_connections_bad_total 7816
telemt_handshake_timeouts_total 17116
telemt_upstream_connect_attempt_total 18892
telemt_upstream_connect_success_total 18797
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 18892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 24855
telemt_me_reconnect_success_total 15164
telemt_me_reader_eof_total 16333
telemt_me_idle_close_by_peer_total 16330
telemt_me_route_drop_no_conn_total 112161
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214348
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 790
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 563
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15674
telemt_me_refill_failed_total 300
telemt_me_writer_restored_same_endpoint_total 15153
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 214216
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 16968927656 (15.80 GB)
telemt_user_octets_to_client{user="hello"} 54301818700 (50.57 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 71731.2 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 583953
telemt_connections_bad_total 8115
telemt_handshake_timeouts_total 13172
telemt_upstream_connect_attempt_total 16670
telemt_upstream_connect_success_total 16512
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 16670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 23931
telemt_me_reconnect_success_total 11868
telemt_me_reader_eof_total 12898
telemt_me_idle_close_by_peer_total 12897
telemt_me_route_drop_no_conn_total 214770
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 501213
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1721
telemt_desync_full_logged_total 587
telemt_desync_suppressed_total 1134
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 513
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12452
telemt_me_refill_failed_total 372
telemt_me_writer_restored_same_endpoint_total 11859
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 502041
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 6296003622 (5.86 GB)
telemt_user_octets_to_client{user="hello"} 161414890015 (150.33 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 71703.1 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278882
telemt_connections_bad_total 56972
telemt_handshake_timeouts_total 3554
telemt_upstream_connect_attempt_total 20940
telemt_upstream_connect_success_total 20479
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 20940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 38356
telemt_me_reconnect_success_total 16478
telemt_me_reader_eof_total 17750
telemt_me_idle_close_by_peer_total 17748
telemt_me_route_drop_no_conn_total 78526
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206677
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1116
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 879
telemt_desync_frames_bucket_total{bucket="1_2"} 558
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17438
telemt_me_refill_failed_total 679
telemt_me_writer_restored_same_endpoint_total 16470
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 960
telemt_user_connections_total{user="hello"} 207164
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 2641643887 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 74531109931 (69.41 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 71864.6 (19h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670524
telemt_connections_bad_total 54002
telemt_handshake_timeouts_total 6684
telemt_upstream_connect_attempt_total 14336
telemt_upstream_connect_success_total 14260
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 20952
telemt_me_reconnect_success_total 10670
telemt_me_reader_eof_total 11636
telemt_me_idle_close_by_peer_total 11636
telemt_me_route_drop_no_conn_total 469937
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 671927
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 917
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 363
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11154
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 10656
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 575490
telemt_user_connections_current{user="hello"} 939
telemt_user_octets_from_client{user="hello"} 8567502716 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 258287524024 (240.55 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 19631.2 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15734
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 308
telemt_upstream_connect_attempt_total 10825
telemt_upstream_connect_success_total 10741
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 10825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 21134
telemt_me_reconnect_success_total 9588
telemt_me_reader_eof_total 10150
telemt_me_idle_close_by_peer_total 10150
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 5700
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14964
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 10041
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 9573
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 15064
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 440872585 (420.45 MB)
telemt_user_octets_to_client{user="hello"} 22973762278 (21.40 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```