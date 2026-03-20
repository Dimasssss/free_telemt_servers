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

# Server Metrics 2026-03-20 09:20:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 57744.9 (16h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1332495
telemt_connections_bad_total 71401
telemt_connections_current 2017
telemt_connections_me_current 2017
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34421
telemt_upstream_connect_attempt_total 11067
telemt_upstream_connect_success_total 10950
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 11067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 7006
telemt_me_reconnect_success_total 6952
telemt_me_reader_eof_total 7356
telemt_me_idle_close_by_peer_total 7354
telemt_me_route_drop_no_conn_total 401786
telemt_me_route_drop_channel_closed_total 245
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1099169
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5759
telemt_desync_full_logged_total 2048
telemt_desync_suppressed_total 3711
telemt_desync_frames_bucket_total{bucket="1_2"} 1214
telemt_desync_frames_bucket_total{bucket="3_10"} 2232
telemt_desync_frames_bucket_total{bucket="gt_10"} 2313
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 128
telemt_me_writer_removed_unexpected_total 7025
telemt_me_writer_restored_same_endpoint_total 6939
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1098720
telemt_user_connections_current{user="hello"} 2017
telemt_user_octets_from_client{user="hello"} 40078699596 (37.33 GB)
telemt_user_octets_to_client{user="hello"} 374443730753 (348.73 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 672
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 74200.7 (20h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5612185
telemt_connections_bad_total 487551
telemt_connections_current 3738
telemt_connections_me_current 3738
telemt_handshake_timeouts_total 116041
telemt_upstream_connect_attempt_total 13655
telemt_upstream_connect_success_total 13362
telemt_upstream_connect_fail_total 293
telemt_upstream_connect_attempts_per_request{bucket="1"} 13655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 293
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12727
telemt_me_reconnect_success_total 8443
telemt_me_reader_eof_total 9031
telemt_me_idle_close_by_peer_total 9030
telemt_me_route_drop_no_conn_total 3522722
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4630729
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17004
telemt_desync_full_logged_total 5694
telemt_desync_suppressed_total 11310
telemt_desync_frames_bucket_total{bucket="1_2"} 3407
telemt_desync_frames_bucket_total{bucket="3_10"} 6658
telemt_desync_frames_bucket_total{bucket="gt_10"} 6939
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3394
telemt_me_writer_close_signal_drop_total 122
telemt_me_writer_removed_unexpected_total 8699
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8388
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 4633053
telemt_user_connections_current{user="hello"} 3738
telemt_user_octets_from_client{user="hello"} 62428573598 (58.14 GB)
telemt_user_octets_to_client{user="hello"} 1529298662266 (1.39 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1392
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 7542.7 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465120
telemt_connections_bad_total 43364
telemt_connections_current 3258
telemt_connections_me_current 3258
telemt_handshake_timeouts_total 5400
telemt_upstream_connect_attempt_total 1498
telemt_upstream_connect_success_total 1498
telemt_upstream_connect_attempts_per_request{bucket="1"} 1498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 699
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1034
telemt_me_reconnect_success_total 1021
telemt_me_reader_eof_total 1026
telemt_me_idle_close_by_peer_total 1026
telemt_me_route_drop_no_conn_total 158064
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376693
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1654
telemt_desync_full_logged_total 539
telemt_desync_suppressed_total 1115
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 767
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 1011
telemt_me_writer_restored_same_endpoint_total 1021
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 376952
telemt_user_connections_current{user="hello"} 3258
telemt_user_octets_from_client{user="hello"} 6113480204 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 149949229547 (139.65 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1205
telemt_user_unique_ips_recent_window{user="hello"} 433
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 74166.4 (20h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7134235
telemt_connections_bad_total 330359
telemt_connections_current 5524
telemt_connections_me_current 5524
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 95723
telemt_upstream_connect_attempt_total 83288
telemt_upstream_connect_success_total 71514
telemt_upstream_connect_fail_total 11774
telemt_upstream_connect_attempts_per_request{bucket="1"} 83288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11774
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 11602
telemt_me_reconnect_success_total 8449
telemt_me_reader_eof_total 8816
telemt_me_idle_close_by_peer_total 8814
telemt_me_route_drop_no_conn_total 10564078
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6159268
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
telemt_desync_total 15307
telemt_desync_full_logged_total 4431
telemt_desync_suppressed_total 10876
telemt_desync_frames_bucket_total{bucket="1_2"} 3390
telemt_desync_frames_bucket_total{bucket="3_10"} 6132
telemt_desync_frames_bucket_total{bucket="gt_10"} 5785
telemt_pool_swap_total 58
telemt_me_writer_close_signal_drop_total 845
telemt_me_writer_removed_unexpected_total 9303
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8445
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 854
telemt_user_connections_total{user="hello"} 6218687
telemt_user_connections_current{user="hello"} 5523
telemt_user_octets_from_client{user="hello"} 55015625151 (51.24 GB)
telemt_user_octets_to_client{user="hello"} 937194135637 (872.83 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1654
telemt_user_unique_ips_recent_window{user="hello"} 1049
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 11749.6 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2623246
telemt_connections_bad_total 212112
telemt_connections_current 6365
telemt_connections_me_current 6365
telemt_handshake_timeouts_total 30519
telemt_upstream_connect_attempt_total 1996
telemt_upstream_connect_success_total 1984
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 1365
telemt_me_reconnect_success_total 1357
telemt_me_reader_eof_total 1390
telemt_me_idle_close_by_peer_total 1389
telemt_me_route_drop_no_conn_total 4025735
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2218983
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4813
telemt_desync_full_logged_total 1374
telemt_desync_suppressed_total 3439
telemt_desync_frames_bucket_total{bucket="1_2"} 879
telemt_desync_frames_bucket_total{bucket="3_10"} 1950
telemt_desync_frames_bucket_total{bucket="gt_10"} 1984
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 1368
telemt_me_writer_restored_same_endpoint_total 1327
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 2213750
telemt_user_connections_current{user="hello"} 6365
telemt_user_octets_from_client{user="hello"} 18737847696 (17.45 GB)
telemt_user_octets_to_client{user="hello"} 279846436504 (260.63 GB)
telemt_user_unique_ips_current{user="hello"} 1942
telemt_user_unique_ips_recent_window{user="hello"} 931
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 1326.7 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37443
telemt_connections_bad_total 12546
telemt_connections_current 713
telemt_connections_me_current 713
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 445
telemt_upstream_connect_attempt_total 1780
telemt_upstream_connect_success_total 1771
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 290
telemt_me_reconnect_success_total 286
telemt_me_reader_eof_total 237
telemt_me_idle_close_by_peer_total 237
telemt_me_route_drop_no_conn_total 9452
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21841
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 20
telemt_me_writer_removed_unexpected_total 249
telemt_me_writer_restored_same_endpoint_total 284
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 23359
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 391910971 (373.76 MB)
telemt_user_octets_to_client{user="hello"} 3633871012 (3.38 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 74131.5 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3821504
telemt_connections_bad_total 244157
telemt_connections_current 5866
telemt_connections_me_current 5866
telemt_handshake_timeouts_total 80921
telemt_upstream_connect_attempt_total 13043
telemt_upstream_connect_success_total 12960
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 13043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9328
telemt_me_reconnect_success_total 9262
telemt_me_reader_eof_total 9795
telemt_me_idle_close_by_peer_total 9794
telemt_me_route_drop_no_conn_total 1371320
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3223000
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15377
telemt_desync_full_logged_total 5112
telemt_desync_suppressed_total 10265
telemt_desync_frames_bucket_total{bucket="1_2"} 3050
telemt_desync_frames_bucket_total{bucket="3_10"} 5590
telemt_desync_frames_bucket_total{bucket="gt_10"} 6737
telemt_pool_swap_total 74
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 9401
telemt_me_writer_restored_same_endpoint_total 9245
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 3220918
telemt_user_connections_current{user="hello"} 5866
telemt_user_octets_from_client{user="hello"} 66797228628 (62.21 GB)
telemt_user_octets_to_client{user="hello"} 1639944730204 (1.49 TB)
telemt_user_unique_ips_current{user="hello"} 1905
telemt_user_unique_ips_recent_window{user="hello"} 708
```