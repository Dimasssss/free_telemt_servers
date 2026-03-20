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

# Server Metrics 2026-03-20 09:55:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 59897.9 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1432081
telemt_connections_bad_total 74582
telemt_connections_current 2023
telemt_connections_me_current 2023
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 37351
telemt_upstream_connect_attempt_total 11423
telemt_upstream_connect_success_total 11304
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 11423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 7271
telemt_me_reconnect_success_total 7216
telemt_me_reader_eof_total 7638
telemt_me_idle_close_by_peer_total 7636
telemt_me_route_drop_no_conn_total 428599
telemt_me_route_drop_channel_closed_total 265
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1174983
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6277
telemt_desync_full_logged_total 2210
telemt_desync_suppressed_total 4067
telemt_desync_frames_bucket_total{bucket="1_2"} 1367
telemt_desync_frames_bucket_total{bucket="3_10"} 2408
telemt_desync_frames_bucket_total{bucket="gt_10"} 2502
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 145
telemt_me_writer_removed_unexpected_total 7294
telemt_me_writer_restored_same_endpoint_total 7203
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1174697
telemt_user_connections_current{user="hello"} 2023
telemt_user_octets_from_client{user="hello"} 41404984972 (38.56 GB)
telemt_user_octets_to_client{user="hello"} 395653906973 (368.48 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 76353.4 (21h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5827975
telemt_connections_bad_total 517254
telemt_connections_current 4031
telemt_connections_me_current 4031
telemt_handshake_timeouts_total 119690
telemt_upstream_connect_attempt_total 14086
telemt_upstream_connect_success_total 13788
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 14086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 14282
telemt_me_reconnect_success_total 8780
telemt_me_reader_eof_total 9408
telemt_me_idle_close_by_peer_total 9407
telemt_me_route_drop_no_conn_total 3604204
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4793022
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17596
telemt_desync_full_logged_total 5920
telemt_desync_suppressed_total 11676
telemt_desync_frames_bucket_total{bucket="1_2"} 3507
telemt_desync_frames_bucket_total{bucket="3_10"} 6893
telemt_desync_frames_bucket_total{bucket="gt_10"} 7196
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3438
telemt_me_writer_close_signal_drop_total 132
telemt_me_writer_removed_unexpected_total 9077
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 8725
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 4794505
telemt_user_connections_current{user="hello"} 4031
telemt_user_octets_from_client{user="hello"} 64840943386 (60.39 GB)
telemt_user_octets_to_client{user="hello"} 1583862856866 (1.44 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1430
telemt_user_unique_ips_recent_window{user="hello"} 554
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 9695.6 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645129
telemt_connections_bad_total 64030
telemt_connections_current 3285
telemt_connections_me_current 3285
telemt_handshake_timeouts_total 7003
telemt_upstream_connect_attempt_total 1777
telemt_upstream_connect_success_total 1777
telemt_upstream_connect_attempts_per_request{bucket="1"} 1777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1227
telemt_me_reconnect_success_total 1214
telemt_me_reader_eof_total 1231
telemt_me_idle_close_by_peer_total 1231
telemt_me_route_drop_no_conn_total 234951
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517770
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2091
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 1397
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 952
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1209
telemt_me_writer_restored_same_endpoint_total 1214
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 518013
telemt_user_connections_current{user="hello"} 3285
telemt_user_octets_from_client{user="hello"} 8367107460 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 197791724491 (184.21 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1291
telemt_user_unique_ips_recent_window{user="hello"} 479
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 76331.3 (21h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5657506
telemt_connections_bad_total 646271
telemt_connections_current 4859
telemt_connections_me_current 4859
telemt_handshake_timeouts_total 83413
telemt_upstream_connect_attempt_total 19791
telemt_upstream_connect_success_total 14732
telemt_upstream_connect_fail_total 5059
telemt_upstream_connect_attempts_per_request{bucket="1"} 19791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6241
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 911
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5059
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 9181
telemt_me_reconnect_success_total 8188
telemt_me_reader_eof_total 8594
telemt_me_idle_close_by_peer_total 8589
telemt_me_route_drop_no_conn_total 3750132
telemt_me_route_drop_channel_closed_total 408
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4108508
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 180
telemt_me_endpoint_quarantine_total 3
telemt_me_kdf_drift_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13435
telemt_desync_full_logged_total 4296
telemt_desync_suppressed_total 9139
telemt_desync_frames_bucket_total{bucket="1_2"} 3113
telemt_desync_frames_bucket_total{bucket="3_10"} 5033
telemt_desync_frames_bucket_total{bucket="gt_10"} 5289
telemt_pool_swap_total 74
telemt_me_writer_close_signal_drop_total 440
telemt_me_writer_removed_unexpected_total 8317
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 8187
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 4187897
telemt_user_connections_current{user="hello"} 4859
telemt_user_octets_from_client{user="hello"} 59853601211 (55.74 GB)
telemt_user_octets_to_client{user="hello"} 1450120174020 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 5696
telemt_user_msgs_to_client{user="hello"} 6360
telemt_user_unique_ips_current{user="hello"} 1624
telemt_user_unique_ips_recent_window{user="hello"} 748
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 76319.8 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7983389
telemt_connections_bad_total 350466
telemt_connections_current 5864
telemt_connections_me_current 5864
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 102414
telemt_upstream_connect_attempt_total 83590
telemt_upstream_connect_success_total 71798
telemt_upstream_connect_fail_total 11792
telemt_upstream_connect_attempts_per_request{bucket="1"} 83590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11792
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 11806
telemt_me_reconnect_success_total 8644
telemt_me_reader_eof_total 9022
telemt_me_idle_close_by_peer_total 9020
telemt_me_route_drop_no_conn_total 12759302
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6932059
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
telemt_desync_total 15987
telemt_desync_full_logged_total 4668
telemt_desync_suppressed_total 11319
telemt_desync_frames_bucket_total{bucket="1_2"} 3535
telemt_desync_frames_bucket_total{bucket="3_10"} 6414
telemt_desync_frames_bucket_total{bucket="gt_10"} 6038
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 854
telemt_me_writer_removed_unexpected_total 9509
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8640
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 865
telemt_user_connections_total{user="hello"} 6991225
telemt_user_connections_current{user="hello"} 5864
telemt_user_octets_from_client{user="hello"} 57632304491 (53.67 GB)
telemt_user_octets_to_client{user="hello"} 959825702197 (893.91 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1746
telemt_user_unique_ips_recent_window{user="hello"} 979
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 13902.7 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3088632
telemt_connections_bad_total 245272
telemt_connections_current 6419
telemt_connections_me_current 6419
telemt_handshake_timeouts_total 36380
telemt_upstream_connect_attempt_total 2339
telemt_upstream_connect_success_total 2326
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 1592
telemt_me_reconnect_success_total 1583
telemt_me_reader_eof_total 1632
telemt_me_idle_close_by_peer_total 1631
telemt_me_route_drop_no_conn_total 4680902
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2609716
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5681
telemt_desync_full_logged_total 1638
telemt_desync_suppressed_total 4043
telemt_desync_frames_bucket_total{bucket="1_2"} 1055
telemt_desync_frames_bucket_total{bucket="3_10"} 2323
telemt_desync_frames_bucket_total{bucket="gt_10"} 2303
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 47
telemt_me_writer_removed_unexpected_total 1600
telemt_me_writer_restored_same_endpoint_total 1553
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 2604473
telemt_user_connections_current{user="hello"} 6419
telemt_user_octets_from_client{user="hello"} 22976777400 (21.40 GB)
telemt_user_octets_to_client{user="hello"} 330796978604 (308.08 GB)
telemt_user_unique_ips_current{user="hello"} 2039
telemt_user_unique_ips_recent_window{user="hello"} 940
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 3480.4 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81114
telemt_connections_bad_total 18443
telemt_connections_current 797
telemt_connections_me_current 797
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 1458
telemt_upstream_connect_attempt_total 2153
telemt_upstream_connect_success_total 2135
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 568
telemt_me_reconnect_success_total 564
telemt_me_reader_eof_total 525
telemt_me_idle_close_by_peer_total 525
telemt_me_route_drop_no_conn_total 24382
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56715
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 139
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 531
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 58233
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 926162419 (883.26 MB)
telemt_user_octets_to_client{user="hello"} 10218701168 (9.52 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 76285.2 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4089166
telemt_connections_bad_total 253380
telemt_connections_current 6363
telemt_connections_me_current 6363
telemt_handshake_timeouts_total 93273
telemt_upstream_connect_attempt_total 13289
telemt_upstream_connect_success_total 13205
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 13289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9487
telemt_me_reconnect_success_total 9419
telemt_me_reader_eof_total 9968
telemt_me_idle_close_by_peer_total 9967
telemt_me_route_drop_no_conn_total 1468958
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3455047
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16476
telemt_desync_full_logged_total 5472
telemt_desync_suppressed_total 11004
telemt_desync_frames_bucket_total{bucket="1_2"} 3442
telemt_desync_frames_bucket_total{bucket="3_10"} 5934
telemt_desync_frames_bucket_total{bucket="gt_10"} 7100
telemt_pool_swap_total 76
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 9565
telemt_me_writer_restored_same_endpoint_total 9402
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 3452954
telemt_user_connections_current{user="hello"} 6363
telemt_user_octets_from_client{user="hello"} 74758003704 (69.62 GB)
telemt_user_octets_to_client{user="hello"} 1735394088384 (1.58 TB)
telemt_user_unique_ips_current{user="hello"} 2071
telemt_user_unique_ips_recent_window{user="hello"} 816
```