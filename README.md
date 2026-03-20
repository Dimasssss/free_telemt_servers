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

# Server Metrics 2026-03-20 10:11:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 60814.9 (16h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1746691
telemt_connections_bad_total 79764
telemt_connections_current 3728
telemt_connections_me_current 3728
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 39585
telemt_upstream_connect_attempt_total 11550
telemt_upstream_connect_success_total 11430
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 11550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 2900
telemt_me_reconnect_attempts_total 7353
telemt_me_reconnect_success_total 7296
telemt_me_reader_eof_total 7726
telemt_me_idle_close_by_peer_total 7724
telemt_me_route_drop_no_conn_total 476390
telemt_me_route_drop_channel_closed_total 387
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1247679
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 26
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6385
telemt_desync_full_logged_total 2243
telemt_desync_suppressed_total 4142
telemt_desync_frames_bucket_total{bucket="1_2"} 1411
telemt_desync_frames_bucket_total{bucket="3_10"} 2457
telemt_desync_frames_bucket_total{bucket="gt_10"} 2517
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 235
telemt_me_writer_removed_unexpected_total 7383
telemt_me_writer_restored_same_endpoint_total 7283
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 1469530
telemt_user_connections_current{user="hello"} 3728
telemt_user_octets_from_client{user="hello"} 43052377412 (40.10 GB)
telemt_user_octets_to_client{user="hello"} 396485671025 (369.26 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 745
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 77270.2 (21h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5928225
telemt_connections_bad_total 524637
telemt_connections_current 4418
telemt_connections_me_current 4418
telemt_handshake_timeouts_total 121334
telemt_upstream_connect_attempt_total 14247
telemt_upstream_connect_success_total 13944
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 14247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 15738
telemt_me_reconnect_success_total 8892
telemt_me_reader_eof_total 9560
telemt_me_idle_close_by_peer_total 9559
telemt_me_route_drop_no_conn_total 3682737
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4873567
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17892
telemt_desync_full_logged_total 6009
telemt_desync_suppressed_total 11883
telemt_desync_frames_bucket_total{bucket="1_2"} 3564
telemt_desync_frames_bucket_total{bucket="3_10"} 7009
telemt_desync_frames_bucket_total{bucket="gt_10"} 7319
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3438
telemt_me_writer_close_signal_drop_total 137
telemt_me_writer_removed_unexpected_total 9231
telemt_me_refill_failed_total 211
telemt_me_writer_restored_same_endpoint_total 8837
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 4875044
telemt_user_connections_current{user="hello"} 4418
telemt_user_octets_from_client{user="hello"} 65957581722 (61.43 GB)
telemt_user_octets_to_client{user="hello"} 1610039876310 (1.46 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1613
telemt_user_unique_ips_recent_window{user="hello"} 661
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 10612.1 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727685
telemt_connections_bad_total 71564
telemt_connections_current 3423
telemt_connections_me_current 3423
telemt_handshake_timeouts_total 8071
telemt_upstream_connect_attempt_total 1912
telemt_upstream_connect_success_total 1912
telemt_upstream_connect_attempts_per_request{bucket="1"} 1912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1317
telemt_me_reconnect_success_total 1301
telemt_me_reader_eof_total 1325
telemt_me_idle_close_by_peer_total 1325
telemt_me_route_drop_no_conn_total 312816
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585018
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2372
telemt_desync_full_logged_total 775
telemt_desync_suppressed_total 1597
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 1053
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1298
telemt_me_writer_restored_same_endpoint_total 1301
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 585122
telemt_user_connections_current{user="hello"} 3423
telemt_user_octets_from_client{user="hello"} 9171150628 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 220934147359 (205.76 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1310
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 77248.1 (21h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5797154
telemt_connections_bad_total 663168
telemt_connections_current 5620
telemt_connections_me_current 5620
telemt_handshake_timeouts_total 86749
telemt_upstream_connect_attempt_total 19970
telemt_upstream_connect_success_total 14910
telemt_upstream_connect_fail_total 5060
telemt_upstream_connect_attempts_per_request{bucket="1"} 19970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 916
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5060
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 3103
telemt_me_reconnect_attempts_total 9313
telemt_me_reconnect_success_total 8320
telemt_me_reader_eof_total 8726
telemt_me_idle_close_by_peer_total 8721
telemt_me_route_drop_no_conn_total 3857615
telemt_me_route_drop_channel_closed_total 434
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4218512
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 180
telemt_me_endpoint_quarantine_total 3
telemt_me_kdf_drift_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13668
telemt_desync_full_logged_total 4393
telemt_desync_suppressed_total 9275
telemt_desync_frames_bucket_total{bucket="1_2"} 3167
telemt_desync_frames_bucket_total{bucket="3_10"} 5118
telemt_desync_frames_bucket_total{bucket="gt_10"} 5383
telemt_pool_swap_total 74
telemt_me_writer_close_signal_drop_total 480
telemt_me_writer_removed_unexpected_total 8451
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 8319
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 4297895
telemt_user_connections_current{user="hello"} 5620
telemt_user_octets_from_client{user="hello"} 60978884211 (56.79 GB)
telemt_user_octets_to_client{user="hello"} 1488164976320 (1.35 TB)
telemt_user_msgs_from_client{user="hello"} 5696
telemt_user_msgs_to_client{user="hello"} 6360
telemt_user_unique_ips_current{user="hello"} 1763
telemt_user_unique_ips_recent_window{user="hello"} 798
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 77236.0 (21h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8359524
telemt_connections_bad_total 367467
telemt_connections_current 6861
telemt_connections_me_current 6861
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 104775
telemt_upstream_connect_attempt_total 83699
telemt_upstream_connect_success_total 71902
telemt_upstream_connect_fail_total 11797
telemt_upstream_connect_attempts_per_request{bucket="1"} 83699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11970
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11797
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 231
telemt_me_reconnect_attempts_total 11872
telemt_me_reconnect_success_total 8705
telemt_me_reader_eof_total 9092
telemt_me_idle_close_by_peer_total 9090
telemt_me_route_drop_no_conn_total 13558791
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7271818
telemt_me_writer_pick_total{mode="p2c",result="full"} 4273
telemt_me_writer_pick_total{mode="p2c",result="closed"} 804
telemt_me_writer_pick_blocking_fallback_total 5052
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16257
telemt_desync_full_logged_total 4760
telemt_desync_suppressed_total 11497
telemt_desync_frames_bucket_total{bucket="1_2"} 3574
telemt_desync_frames_bucket_total{bucket="3_10"} 6550
telemt_desync_frames_bucket_total{bucket="gt_10"} 6133
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 856
telemt_me_writer_removed_unexpected_total 9574
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8701
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 869
telemt_user_connections_total{user="hello"} 7330836
telemt_user_connections_current{user="hello"} 6861
telemt_user_octets_from_client{user="hello"} 59054081963 (55.00 GB)
telemt_user_octets_to_client{user="hello"} 970542983109 (903.89 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1788
telemt_user_unique_ips_recent_window{user="hello"} 1142
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 14819.2 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3429098
telemt_connections_bad_total 254762
telemt_connections_current 6996
telemt_connections_me_current 6996
telemt_handshake_timeouts_total 38763
telemt_upstream_connect_attempt_total 2482
telemt_upstream_connect_success_total 2468
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 1691
telemt_me_reconnect_success_total 1681
telemt_me_reader_eof_total 1741
telemt_me_idle_close_by_peer_total 1740
telemt_me_route_drop_no_conn_total 5313783
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2918543
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6214
telemt_desync_full_logged_total 1779
telemt_desync_suppressed_total 4435
telemt_desync_frames_bucket_total{bucket="1_2"} 1144
telemt_desync_frames_bucket_total{bucket="3_10"} 2587
telemt_desync_frames_bucket_total{bucket="gt_10"} 2483
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 48
telemt_me_writer_removed_unexpected_total 1700
telemt_me_writer_restored_same_endpoint_total 1651
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2913167
telemt_user_connections_current{user="hello"} 6996
telemt_user_octets_from_client{user="hello"} 24913107520 (23.20 GB)
telemt_user_octets_to_client{user="hello"} 350274393748 (326.22 GB)
telemt_user_unique_ips_current{user="hello"} 2108
telemt_user_unique_ips_recent_window{user="hello"} 1332
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 4398.6 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103447
telemt_connections_bad_total 23705
telemt_connections_current 899
telemt_connections_me_current 899
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 1624
telemt_upstream_connect_attempt_total 2304
telemt_upstream_connect_success_total 2283
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 673
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 643
telemt_me_idle_close_by_peer_total 643
telemt_me_route_drop_no_conn_total 36819
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72923
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
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_restored_same_endpoint_total 666
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 74443
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 1172983019 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 13397701936 (12.48 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 77200.9 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4240266
telemt_connections_bad_total 288986
telemt_connections_current 6444
telemt_connections_me_current 6444
telemt_handshake_timeouts_total 97618
telemt_upstream_connect_attempt_total 13459
telemt_upstream_connect_success_total 13375
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 13459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9612
telemt_me_reconnect_success_total 9543
telemt_me_reader_eof_total 10094
telemt_me_idle_close_by_peer_total 10093
telemt_me_route_drop_no_conn_total 1534978
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3560040
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16968
telemt_desync_full_logged_total 5614
telemt_desync_suppressed_total 11354
telemt_desync_frames_bucket_total{bucket="1_2"} 3564
telemt_desync_frames_bucket_total{bucket="3_10"} 6137
telemt_desync_frames_bucket_total{bucket="gt_10"} 7267
telemt_pool_swap_total 76
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 9690
telemt_me_writer_restored_same_endpoint_total 9526
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 3557939
telemt_user_connections_current{user="hello"} 6444
telemt_user_octets_from_client{user="hello"} 78223852380 (72.85 GB)
telemt_user_octets_to_client{user="hello"} 1779336078456 (1.62 TB)
telemt_user_unique_ips_current{user="hello"} 2041
telemt_user_unique_ips_recent_window{user="hello"} 796
```