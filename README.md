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

# Server Metrics 2026-03-17 21:17:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 95522.9 (26h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1176605
telemt_connections_bad_total 8633
telemt_handshake_timeouts_total 31505
telemt_upstream_connect_attempt_total 21714
telemt_upstream_connect_success_total 21223
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 21714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31259
telemt_me_reconnect_success_total 14129
telemt_me_reader_eof_total 15356
telemt_me_idle_close_by_peer_total 15355
telemt_me_route_drop_no_conn_total 525415
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1078260
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7165
telemt_desync_full_logged_total 2060
telemt_desync_suppressed_total 5105
telemt_desync_frames_bucket_total{bucket="1_2"} 1918
telemt_desync_frames_bucket_total{bucket="3_10"} 2716
telemt_desync_frames_bucket_total{bucket="gt_10"} 2531
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 14874
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14107
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 745
telemt_user_connections_total{user="hello"} 1072493
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 19163520667 (17.85 GB)
telemt_user_octets_to_client{user="hello"} 380801189331 (354.65 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 95774.2 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1222570
telemt_connections_bad_total 59567
telemt_handshake_timeouts_total 43959
telemt_upstream_connect_attempt_total 457238
telemt_upstream_connect_success_total 456348
telemt_upstream_connect_fail_total 890
telemt_upstream_connect_attempts_per_request{bucket="1"} 457238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 890
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57703
telemt_me_reconnect_success_total 14550
telemt_me_reader_eof_total 16516
telemt_me_idle_close_by_peer_total 16516
telemt_me_route_drop_no_conn_total 310730
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618529
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2744
telemt_desync_full_logged_total 872
telemt_desync_suppressed_total 1872
telemt_desync_frames_bucket_total{bucket="1_2"} 520
telemt_desync_frames_bucket_total{bucket="3_10"} 1145
telemt_desync_frames_bucket_total{bucket="gt_10"} 1079
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16080
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14534
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1530
telemt_user_connections_total{user="hello"} 1054959
telemt_user_connections_current{user="hello"} 1315
telemt_user_octets_from_client{user="hello"} 14620921026 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 351575120346 (327.43 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 95550.3 (26h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 687398
telemt_connections_bad_total 39494
telemt_handshake_timeouts_total 22572
telemt_upstream_connect_attempt_total 22866
telemt_upstream_connect_success_total 22733
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 22866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38563
telemt_me_reconnect_success_total 17888
telemt_me_reader_eof_total 19522
telemt_me_idle_close_by_peer_total 19515
telemt_me_route_drop_no_conn_total 290735
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592363
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1897
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 1319
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 622
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 18778
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17876
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 890
telemt_user_connections_total{user="hello"} 590634
telemt_user_connections_current{user="hello"} 979
telemt_user_octets_from_client{user="hello"} 29445113232 (27.42 GB)
telemt_user_octets_to_client{user="hello"} 251738026556 (234.45 GB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 95609.9 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1189089
telemt_connections_bad_total 37148
telemt_handshake_timeouts_total 21265
telemt_upstream_connect_attempt_total 82473
telemt_upstream_connect_success_total 82051
telemt_upstream_connect_fail_total 422
telemt_upstream_connect_attempts_per_request{bucket="1"} 82473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11942
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 422
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 34194
telemt_me_reconnect_success_total 13878
telemt_me_reader_eof_total 15285
telemt_me_idle_close_by_peer_total 15284
telemt_me_route_drop_no_conn_total 494063
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 971255
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3339
telemt_desync_full_logged_total 1070
telemt_desync_suppressed_total 2269
telemt_desync_frames_bucket_total{bucket="1_2"} 822
telemt_desync_frames_bucket_total{bucket="3_10"} 1415
telemt_desync_frames_bucket_total{bucket="gt_10"} 1102
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14771
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13869
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 893
telemt_user_connections_total{user="hello"} 1033765
telemt_user_connections_current{user="hello"} 1107
telemt_user_octets_from_client{user="hello"} 15441817323 (14.38 GB)
telemt_user_octets_to_client{user="hello"} 435386489577 (405.49 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 95581.6 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 741769
telemt_connections_bad_total 90888
telemt_handshake_timeouts_total 6282
telemt_upstream_connect_attempt_total 41266
telemt_upstream_connect_success_total 40715
telemt_upstream_connect_fail_total 551
telemt_upstream_connect_attempts_per_request{bucket="1"} 41266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 395
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 551
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51913
telemt_me_reconnect_success_total 19428
telemt_me_reader_eof_total 21155
telemt_me_idle_close_by_peer_total 21153
telemt_me_route_drop_no_conn_total 232741
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588489
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2694
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 1913
telemt_desync_frames_bucket_total{bucket="1_2"} 884
telemt_desync_frames_bucket_total{bucket="3_10"} 1077
telemt_desync_frames_bucket_total{bucket="gt_10"} 733
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20773
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19420
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1345
telemt_user_connections_total{user="hello"} 605103
telemt_user_connections_current{user="hello"} 1044
telemt_user_octets_from_client{user="hello"} 11813799892 (11.00 GB)
telemt_user_octets_to_client{user="hello"} 296775437220 (276.39 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 95742.6 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 985034
telemt_connections_bad_total 71695
telemt_handshake_timeouts_total 9311
telemt_upstream_connect_attempt_total 18947
telemt_upstream_connect_success_total 18835
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 18947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9731
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25314
telemt_me_reconnect_success_total 14037
telemt_me_reader_eof_total 15249
telemt_me_idle_close_by_peer_total 15247
telemt_me_route_drop_no_conn_total 682305
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 980166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2012
telemt_desync_full_logged_total 702
telemt_desync_suppressed_total 1310
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 767
telemt_desync_frames_bucket_total{bucket="gt_10"} 792
telemt_pool_swap_total 81
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14620
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14023
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 843198
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 13135567644 (12.23 GB)
telemt_user_octets_to_client{user="hello"} 362166467436 (337.29 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 43509.8 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320597
telemt_connections_bad_total 41566
telemt_handshake_timeouts_total 9733
telemt_upstream_connect_attempt_total 17596
telemt_upstream_connect_success_total 17433
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 17596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26665
telemt_me_reconnect_success_total 15072
telemt_me_reader_eof_total 15929
telemt_me_idle_close_by_peer_total 15929
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 78755
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245559
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 783
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 558
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15611
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15044
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 245502
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 20908533253 (19.47 GB)
telemt_user_octets_to_client{user="hello"} 205517740454 (191.40 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 69
```