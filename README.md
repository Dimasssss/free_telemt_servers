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

# Server Metrics 2026-03-20 07:00:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 49369.7 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1009645
telemt_connections_bad_total 61770
telemt_connections_current 1775
telemt_connections_me_current 1775
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 26348
telemt_upstream_connect_attempt_total 9492
telemt_upstream_connect_success_total 9386
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 9492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5878
telemt_me_reconnect_success_total 5834
telemt_me_reader_eof_total 6179
telemt_me_idle_close_by_peer_total 6178
telemt_me_route_drop_no_conn_total 290236
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 825547
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4263
telemt_desync_full_logged_total 1538
telemt_desync_suppressed_total 2725
telemt_desync_frames_bucket_total{bucket="1_2"} 842
telemt_desync_frames_bucket_total{bucket="3_10"} 1658
telemt_desync_frames_bucket_total{bucket="gt_10"} 1763
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 52
telemt_me_writer_removed_unexpected_total 5897
telemt_me_writer_restored_same_endpoint_total 5821
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 824943
telemt_user_connections_current{user="hello"} 1775
telemt_user_octets_from_client{user="hello"} 34618810780 (32.24 GB)
telemt_user_octets_to_client{user="hello"} 284199049505 (264.68 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 591
telemt_user_unique_ips_recent_window{user="hello"} 275
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 65825.7 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4473178
telemt_connections_bad_total 424905
telemt_connections_current 6178
telemt_connections_me_current 6178
telemt_handshake_timeouts_total 99837
telemt_upstream_connect_attempt_total 12298
telemt_upstream_connect_success_total 12070
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 12298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 11815
telemt_me_reconnect_success_total 7558
telemt_me_reader_eof_total 8085
telemt_me_idle_close_by_peer_total 8084
telemt_me_route_drop_no_conn_total 2141214
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3652124
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14305
telemt_desync_full_logged_total 4757
telemt_desync_suppressed_total 9548
telemt_desync_frames_bucket_total{bucket="1_2"} 2840
telemt_desync_frames_bucket_total{bucket="3_10"} 5569
telemt_desync_frames_bucket_total{bucket="gt_10"} 5896
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 7791
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7503
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 3651784
telemt_user_connections_current{user="hello"} 6178
telemt_user_octets_from_client{user="hello"} 52420236234 (48.82 GB)
telemt_user_octets_to_client{user="hello"} 1329681216962 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1897
telemt_user_unique_ips_recent_window{user="hello"} 911
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 65791.1 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4270793
telemt_connections_bad_total 280922
telemt_connections_current 5546
telemt_connections_me_current 5546
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 61284
telemt_upstream_connect_attempt_total 67939
telemt_upstream_connect_success_total 63204
telemt_upstream_connect_fail_total 4735
telemt_upstream_connect_attempts_per_request{bucket="1"} 67939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4735
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10505
telemt_me_reconnect_success_total 7521
telemt_me_reader_eof_total 7854
telemt_me_idle_close_by_peer_total 7853
telemt_me_route_drop_no_conn_total 4466223
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3559659
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12114
telemt_desync_full_logged_total 3606
telemt_desync_suppressed_total 8508
telemt_desync_frames_bucket_total{bucket="1_2"} 2804
telemt_desync_frames_bucket_total{bucket="3_10"} 4715
telemt_desync_frames_bucket_total{bucket="gt_10"} 4595
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 676
telemt_me_writer_removed_unexpected_total 8247
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7517
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 3610794
telemt_user_connections_current{user="hello"} 5546
telemt_user_octets_from_client{user="hello"} 45155314340 (42.05 GB)
telemt_user_octets_to_client{user="hello"} 841633325655 (783.83 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1471
telemt_user_unique_ips_recent_window{user="hello"} 793
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 3374.5 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465822
telemt_connections_bad_total 51496
telemt_connections_current 4913
telemt_connections_me_current 4913
telemt_handshake_timeouts_total 9484
telemt_upstream_connect_attempt_total 533
telemt_upstream_connect_success_total 530
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 329
telemt_me_reconnect_success_total 327
telemt_me_reader_eof_total 306
telemt_me_idle_close_by_peer_total 306
telemt_me_route_drop_no_conn_total 457854
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373194
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1093
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 452
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 319
telemt_me_writer_restored_same_endpoint_total 297
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 373145
telemt_user_connections_current{user="hello"} 4913
telemt_user_octets_from_client{user="hello"} 6415874316 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 86278544812 (80.35 GB)
telemt_user_unique_ips_current{user="hello"} 1576
telemt_user_unique_ips_recent_window{user="hello"} 785
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 3309.9 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51539
telemt_connections_bad_total 9524
telemt_connections_current 619
telemt_connections_me_current 619
telemt_handshake_timeouts_total 592
telemt_upstream_connect_attempt_total 646
telemt_upstream_connect_success_total 639
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 439
telemt_me_reconnect_success_total 437
telemt_me_reader_eof_total 431
telemt_me_idle_close_by_peer_total 431
telemt_me_route_drop_no_conn_total 30447
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52375
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 438
telemt_me_writer_restored_same_endpoint_total 429
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 39573
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 338846280 (323.15 MB)
telemt_user_octets_to_client{user="hello"} 15211084884 (14.17 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 65756.0 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2868817
telemt_connections_bad_total 182599
telemt_connections_current 4933
telemt_connections_me_current 4933
telemt_handshake_timeouts_total 52005
telemt_upstream_connect_attempt_total 11603
telemt_upstream_connect_success_total 11531
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 11603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8321
telemt_me_reconnect_success_total 8267
telemt_me_reader_eof_total 8743
telemt_me_idle_close_by_peer_total 8743
telemt_me_route_drop_no_conn_total 974610
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2405358
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12022
telemt_desync_full_logged_total 3934
telemt_desync_suppressed_total 8088
telemt_desync_frames_bucket_total{bucket="1_2"} 2421
telemt_desync_frames_bucket_total{bucket="3_10"} 4222
telemt_desync_frames_bucket_total{bucket="gt_10"} 5379
telemt_pool_swap_total 67
telemt_me_writer_close_signal_drop_total 47
telemt_me_writer_removed_unexpected_total 8383
telemt_me_writer_restored_same_endpoint_total 8250
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 2404244
telemt_user_connections_current{user="hello"} 4933
telemt_user_octets_from_client{user="hello"} 52703187224 (49.08 GB)
telemt_user_octets_to_client{user="hello"} 1259228601876 (1.15 TB)
telemt_user_unique_ips_current{user="hello"} 1462
telemt_user_unique_ips_recent_window{user="hello"} 716
```