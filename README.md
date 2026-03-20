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
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

# Server Metrics 2026-03-20 10:16:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 61122.2 (16h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1854598
telemt_connections_bad_total 81696
telemt_connections_current 3748
telemt_connections_me_current 3748
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 40189
telemt_upstream_connect_attempt_total 11570
telemt_upstream_connect_success_total 11450
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 11570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 4906
telemt_me_reconnect_attempts_total 7373
telemt_me_reconnect_success_total 7315
telemt_me_reader_eof_total 7747
telemt_me_idle_close_by_peer_total 7745
telemt_me_route_drop_no_conn_total 482056
telemt_me_route_drop_channel_closed_total 484
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1284135
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 26
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6414
telemt_desync_full_logged_total 2252
telemt_desync_suppressed_total 4162
telemt_desync_frames_bucket_total{bucket="1_2"} 1428
telemt_desync_frames_bucket_total{bucket="3_10"} 2467
telemt_desync_frames_bucket_total{bucket="gt_10"} 2519
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 255
telemt_me_writer_removed_unexpected_total 7404
telemt_me_writer_restored_same_endpoint_total 7302
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 1569951
telemt_user_connections_current{user="hello"} 3748
telemt_user_octets_from_client{user="hello"} 43566279724 (40.57 GB)
telemt_user_octets_to_client{user="hello"} 396485752653 (369.26 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 717
telemt_user_unique_ips_recent_window{user="hello"} 620
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 77577.1 (21h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5963367
telemt_connections_bad_total 527784
telemt_connections_current 4134
telemt_connections_me_current 4134
telemt_handshake_timeouts_total 122203
telemt_upstream_connect_attempt_total 14330
telemt_upstream_connect_success_total 14021
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 14330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 16603
telemt_me_reconnect_success_total 8925
telemt_me_reader_eof_total 9619
telemt_me_idle_close_by_peer_total 9618
telemt_me_route_drop_no_conn_total 3708216
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4899993
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17998
telemt_desync_full_logged_total 6047
telemt_desync_suppressed_total 11951
telemt_desync_frames_bucket_total{bucket="1_2"} 3587
telemt_desync_frames_bucket_total{bucket="3_10"} 7049
telemt_desync_frames_bucket_total{bucket="gt_10"} 7362
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3438
telemt_me_writer_close_signal_drop_total 137
telemt_me_writer_removed_unexpected_total 9290
telemt_me_refill_failed_total 237
telemt_me_writer_restored_same_endpoint_total 8870
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 4901463
telemt_user_connections_current{user="hello"} 4134
telemt_user_octets_from_client{user="hello"} 66243888750 (61.69 GB)
telemt_user_octets_to_client{user="hello"} 1618980815186 (1.47 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1555
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 10919.0 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752512
telemt_connections_bad_total 73875
telemt_connections_current 3507
telemt_connections_me_current 3507
telemt_handshake_timeouts_total 8480
telemt_upstream_connect_attempt_total 1972
telemt_upstream_connect_success_total 1972
telemt_upstream_connect_attempts_per_request{bucket="1"} 1972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1333
telemt_me_reconnect_success_total 1316
telemt_me_reader_eof_total 1341
telemt_me_idle_close_by_peer_total 1341
telemt_me_route_drop_no_conn_total 325072
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605190
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2420
telemt_desync_full_logged_total 794
telemt_desync_suppressed_total 1626
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 855
telemt_desync_frames_bucket_total{bucket="gt_10"} 1065
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 1314
telemt_me_writer_restored_same_endpoint_total 1316
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 605305
telemt_user_connections_current{user="hello"} 3507
telemt_user_octets_from_client{user="hello"} 9650693044 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 227562457103 (211.93 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1320
telemt_user_unique_ips_recent_window{user="hello"} 460
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 77555.0 (21h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5846150
telemt_connections_bad_total 669802
telemt_connections_current 5497
telemt_connections_me_current 5497
telemt_handshake_timeouts_total 87737
telemt_upstream_connect_attempt_total 20059
telemt_upstream_connect_success_total 14998
telemt_upstream_connect_fail_total 5061
telemt_upstream_connect_attempts_per_request{bucket="1"} 20059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 918
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5061
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 3103
telemt_me_reconnect_attempts_total 9358
telemt_me_reconnect_success_total 8365
telemt_me_reader_eof_total 8774
telemt_me_idle_close_by_peer_total 8769
telemt_me_route_drop_no_conn_total 3907867
telemt_me_route_drop_channel_closed_total 440
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4257319
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 180
telemt_me_endpoint_quarantine_total 3
telemt_me_kdf_drift_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13730
telemt_desync_full_logged_total 4416
telemt_desync_suppressed_total 9314
telemt_desync_frames_bucket_total{bucket="1_2"} 3176
telemt_desync_frames_bucket_total{bucket="3_10"} 5146
telemt_desync_frames_bucket_total{bucket="gt_10"} 5408
telemt_pool_swap_total 75
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 506
telemt_me_writer_removed_unexpected_total 8497
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 8364
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 4336603
telemt_user_connections_current{user="hello"} 5497
telemt_user_octets_from_client{user="hello"} 61401315511 (57.18 GB)
telemt_user_octets_to_client{user="hello"} 1498535720640 (1.36 TB)
telemt_user_msgs_from_client{user="hello"} 5696
telemt_user_msgs_to_client{user="hello"} 6360
telemt_user_unique_ips_current{user="hello"} 1759
telemt_user_unique_ips_recent_window{user="hello"} 749
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 100.9 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36950
telemt_connections_bad_total 1227
telemt_connections_current 5857
telemt_connections_me_current 5857
telemt_handshake_timeouts_total 194
telemt_upstream_connect_attempt_total 95
telemt_upstream_connect_success_total 94
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 95
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 28
telemt_me_reconnect_success_total 28
telemt_me_route_drop_no_conn_total 29987
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33075
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 1169
telemt_user_connections_total{user="hello"} 33068
telemt_user_connections_current{user="hello"} 5857
telemt_user_octets_from_client{user="hello"} 138311184 (131.90 MB)
telemt_user_octets_to_client{user="hello"} 1112904844 (1.04 GB)
telemt_user_unique_ips_current{user="hello"} 1581
telemt_user_unique_ips_recent_window{user="hello"} 985
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 15126.1 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3563229
telemt_connections_bad_total 257884
telemt_connections_current 6786
telemt_connections_me_current 6786
telemt_handshake_timeouts_total 39589
telemt_upstream_connect_attempt_total 2503
telemt_upstream_connect_success_total 2489
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 256
telemt_me_reconnect_attempts_total 1712
telemt_me_reconnect_success_total 1702
telemt_me_reader_eof_total 1762
telemt_me_idle_close_by_peer_total 1761
telemt_me_route_drop_no_conn_total 5840058
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3041610
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6397
telemt_desync_full_logged_total 1832
telemt_desync_suppressed_total 4565
telemt_desync_frames_bucket_total{bucket="1_2"} 1185
telemt_desync_frames_bucket_total{bucket="3_10"} 2666
telemt_desync_frames_bucket_total{bucket="gt_10"} 2546
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 48
telemt_me_writer_removed_unexpected_total 1721
telemt_me_writer_restored_same_endpoint_total 1672
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 3036228
telemt_user_connections_current{user="hello"} 6786
telemt_user_octets_from_client{user="hello"} 25867453812 (24.09 GB)
telemt_user_octets_to_client{user="hello"} 354915735404 (330.54 GB)
telemt_user_unique_ips_current{user="hello"} 2092
telemt_user_unique_ips_recent_window{user="hello"} 1267
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 4703.7 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109526
telemt_connections_bad_total 23712
telemt_connections_current 875
telemt_connections_me_current 875
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 1663
telemt_upstream_connect_attempt_total 2388
telemt_upstream_connect_success_total 2365
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 514
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 712
telemt_me_reconnect_success_total 707
telemt_me_reader_eof_total 686
telemt_me_idle_close_by_peer_total 686
telemt_me_route_drop_no_conn_total 40650
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78540
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 172
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 677
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 80060
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 1241960775 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 14505607488 (13.51 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 77508.1 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4277866
telemt_connections_bad_total 290017
telemt_connections_current 6716
telemt_connections_me_current 6716
telemt_handshake_timeouts_total 99695
telemt_upstream_connect_attempt_total 13534
telemt_upstream_connect_success_total 13449
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 13534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9643
telemt_me_reconnect_success_total 9574
telemt_me_reader_eof_total 10125
telemt_me_idle_close_by_peer_total 10124
telemt_me_route_drop_no_conn_total 1552760
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3593208
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17121
telemt_desync_full_logged_total 5659
telemt_desync_suppressed_total 11462
telemt_desync_frames_bucket_total{bucket="1_2"} 3600
telemt_desync_frames_bucket_total{bucket="3_10"} 6192
telemt_desync_frames_bucket_total{bucket="gt_10"} 7329
telemt_pool_swap_total 76
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 9721
telemt_me_writer_restored_same_endpoint_total 9557
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 3591083
telemt_user_connections_current{user="hello"} 6716
telemt_user_octets_from_client{user="hello"} 79783874232 (74.30 GB)
telemt_user_octets_to_client{user="hello"} 1797927131608 (1.64 TB)
telemt_user_unique_ips_current{user="hello"} 2087
telemt_user_unique_ips_recent_window{user="hello"} 822
```