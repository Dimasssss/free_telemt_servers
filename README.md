# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 07:05:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 49674.8 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021010
telemt_connections_bad_total 61853
telemt_connections_current 1863
telemt_connections_me_current 1863
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 26510
telemt_upstream_connect_attempt_total 9593
telemt_upstream_connect_success_total 9485
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 9593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 5933
telemt_me_reconnect_success_total 5888
telemt_me_reader_eof_total 6235
telemt_me_idle_close_by_peer_total 6234
telemt_me_route_drop_no_conn_total 294379
telemt_me_route_drop_channel_closed_total 115
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 836227
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4305
telemt_desync_full_logged_total 1552
telemt_desync_suppressed_total 2753
telemt_desync_frames_bucket_total{bucket="1_2"} 858
telemt_desync_frames_bucket_total{bucket="3_10"} 1668
telemt_desync_frames_bucket_total{bucket="gt_10"} 1779
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 58
telemt_me_writer_removed_unexpected_total 5953
telemt_me_writer_restored_same_endpoint_total 5875
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 835656
telemt_user_connections_current{user="hello"} 1863
telemt_user_octets_from_client{user="hello"} 34742294624 (32.36 GB)
telemt_user_octets_to_client{user="hello"} 288507392865 (268.69 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 66129.9 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4562050
telemt_connections_bad_total 431097
telemt_connections_current 6893
telemt_connections_me_current 6893
telemt_handshake_timeouts_total 100463
telemt_upstream_connect_attempt_total 12335
telemt_upstream_connect_success_total 12107
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 12335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 11851
telemt_me_reconnect_success_total 7593
telemt_me_reader_eof_total 8125
telemt_me_idle_close_by_peer_total 8124
telemt_me_route_drop_no_conn_total 2281631
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3730655
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14544
telemt_desync_full_logged_total 4820
telemt_desync_suppressed_total 9724
telemt_desync_frames_bucket_total{bucket="1_2"} 2883
telemt_desync_frames_bucket_total{bucket="3_10"} 5657
telemt_desync_frames_bucket_total{bucket="gt_10"} 6004
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 81
telemt_me_writer_removed_unexpected_total 7826
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7538
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 3730378
telemt_user_connections_current{user="hello"} 6893
telemt_user_octets_from_client{user="hello"} 52997292378 (49.36 GB)
telemt_user_octets_to_client{user="hello"} 1336270176850 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1905
telemt_user_unique_ips_recent_window{user="hello"} 1114
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 66109.0 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4108935
telemt_connections_bad_total 534983
telemt_connections_current 4097
telemt_connections_me_current 4097
telemt_handshake_timeouts_total 63765
telemt_upstream_connect_attempt_total 12210
telemt_upstream_connect_success_total 12105
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 12210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3075
telemt_me_reconnect_attempts_total 8310
telemt_me_reconnect_success_total 7349
telemt_me_reader_eof_total 7689
telemt_me_idle_close_by_peer_total 7684
telemt_me_route_drop_no_conn_total 2741968
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2946577
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10208
telemt_desync_full_logged_total 3206
telemt_desync_suppressed_total 7002
telemt_desync_frames_bucket_total{bucket="1_2"} 2491
telemt_desync_frames_bucket_total{bucket="3_10"} 3899
telemt_desync_frames_bucket_total{bucket="gt_10"} 3818
telemt_pool_swap_total 65
telemt_me_writer_close_signal_drop_total 316
telemt_me_writer_removed_unexpected_total 7445
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7348
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 2952965
telemt_user_connections_current{user="hello"} 4096
telemt_user_octets_from_client{user="hello"} 41215839378 (38.39 GB)
telemt_user_octets_to_client{user="hello"} 1102060015056 (1.00 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1299
telemt_user_unique_ips_recent_window{user="hello"} 674
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 66096.2 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4383118
telemt_connections_bad_total 282955
telemt_connections_current 5483
telemt_connections_me_current 5483
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 62413
telemt_upstream_connect_attempt_total 67979
telemt_upstream_connect_success_total 63243
telemt_upstream_connect_fail_total 4736
telemt_upstream_connect_attempts_per_request{bucket="1"} 67979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4736
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10540
telemt_me_reconnect_success_total 7555
telemt_me_reader_eof_total 7894
telemt_me_idle_close_by_peer_total 7893
telemt_me_route_drop_no_conn_total 4694238
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3663713
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12380
telemt_desync_full_logged_total 3652
telemt_desync_suppressed_total 8728
telemt_desync_frames_bucket_total{bucket="1_2"} 2836
telemt_desync_frames_bucket_total{bucket="3_10"} 4850
telemt_desync_frames_bucket_total{bucket="gt_10"} 4694
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 677
telemt_me_writer_removed_unexpected_total 8281
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7551
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 3714894
telemt_user_connections_current{user="hello"} 5483
telemt_user_octets_from_client{user="hello"} 45514415556 (42.39 GB)
telemt_user_octets_to_client{user="hello"} 845103419335 (787.06 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1543
telemt_user_unique_ips_recent_window{user="hello"} 1030
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 3679.3 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 536759
telemt_connections_bad_total 54318
telemt_connections_current 5427
telemt_connections_me_current 5427
telemt_handshake_timeouts_total 10410
telemt_upstream_connect_attempt_total 583
telemt_upstream_connect_success_total 580
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 346
telemt_me_reconnect_success_total 344
telemt_me_reader_eof_total 322
telemt_me_idle_close_by_peer_total 322
telemt_me_route_drop_no_conn_total 579766
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437343
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1252
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 864
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 515
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 336
telemt_me_writer_restored_same_endpoint_total 314
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 437297
telemt_user_connections_current{user="hello"} 5427
telemt_user_octets_from_client{user="hello"} 6863013188 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 94019686080 (87.56 GB)
telemt_user_unique_ips_current{user="hello"} 1602
telemt_user_unique_ips_recent_window{user="hello"} 1195
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 3614.8 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57271
telemt_connections_bad_total 10483
telemt_connections_current 730
telemt_connections_me_current 730
telemt_handshake_timeouts_total 684
telemt_upstream_connect_attempt_total 670
telemt_upstream_connect_success_total 663
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 463
telemt_me_reconnect_success_total 460
telemt_me_reader_eof_total 454
telemt_me_idle_close_by_peer_total 454
telemt_me_route_drop_no_conn_total 32267
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56745
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 217
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 461
telemt_me_writer_restored_same_endpoint_total 452
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 43879
telemt_user_connections_current{user="hello"} 730
telemt_user_octets_from_client{user="hello"} 370267464 (353.11 MB)
telemt_user_octets_to_client{user="hello"} 17200284432 (16.02 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 66061.1 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2899108
telemt_connections_bad_total 182933
telemt_connections_current 5315
telemt_connections_me_current 5315
telemt_handshake_timeouts_total 52769
telemt_upstream_connect_attempt_total 11675
telemt_upstream_connect_success_total 11601
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 11675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8366
telemt_me_reconnect_success_total 8312
telemt_me_reader_eof_total 8791
telemt_me_idle_close_by_peer_total 8791
telemt_me_route_drop_no_conn_total 988197
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2433230
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12153
telemt_desync_full_logged_total 3971
telemt_desync_suppressed_total 8182
telemt_desync_frames_bucket_total{bucket="1_2"} 2454
telemt_desync_frames_bucket_total{bucket="3_10"} 4262
telemt_desync_frames_bucket_total{bucket="gt_10"} 5437
telemt_pool_swap_total 68
telemt_me_writer_close_signal_drop_total 48
telemt_me_writer_removed_unexpected_total 8428
telemt_me_writer_restored_same_endpoint_total 8295
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 2432122
telemt_user_connections_current{user="hello"} 5315
telemt_user_octets_from_client{user="hello"} 53006097028 (49.37 GB)
telemt_user_octets_to_client{user="hello"} 1272785802040 (1.16 TB)
telemt_user_unique_ips_current{user="hello"} 1567
telemt_user_unique_ips_recent_window{user="hello"} 745
```