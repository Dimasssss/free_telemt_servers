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

# Server Metrics 2026-03-20 09:30:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 58354.3 (16h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1361318
telemt_connections_bad_total 72446
telemt_connections_current 2046
telemt_connections_me_current 2046
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 35013
telemt_upstream_connect_attempt_total 11124
telemt_upstream_connect_success_total 11007
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 11124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 7063
telemt_me_reconnect_success_total 7008
telemt_me_reader_eof_total 7418
telemt_me_idle_close_by_peer_total 7416
telemt_me_route_drop_no_conn_total 409159
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1120420
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5886
telemt_desync_full_logged_total 2084
telemt_desync_suppressed_total 3802
telemt_desync_frames_bucket_total{bucket="1_2"} 1250
telemt_desync_frames_bucket_total{bucket="3_10"} 2277
telemt_desync_frames_bucket_total{bucket="gt_10"} 2359
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 131
telemt_me_writer_removed_unexpected_total 7083
telemt_me_writer_restored_same_endpoint_total 6995
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1120044
telemt_user_connections_current{user="hello"} 2046
telemt_user_octets_from_client{user="hello"} 40669393412 (37.88 GB)
telemt_user_octets_to_client{user="hello"} 380228763633 (354.12 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 674
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 74810.1 (20h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5683189
telemt_connections_bad_total 505047
telemt_connections_current 3851
telemt_connections_me_current 3851
telemt_handshake_timeouts_total 117105
telemt_upstream_connect_attempt_total 13754
telemt_upstream_connect_success_total 13458
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 13754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12780
telemt_me_reconnect_success_total 8496
telemt_me_reader_eof_total 9086
telemt_me_idle_close_by_peer_total 9085
telemt_me_route_drop_no_conn_total 3543206
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4676189
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17243
telemt_desync_full_logged_total 5767
telemt_desync_suppressed_total 11476
telemt_desync_frames_bucket_total{bucket="1_2"} 3454
telemt_desync_frames_bucket_total{bucket="3_10"} 6759
telemt_desync_frames_bucket_total{bucket="gt_10"} 7030
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3394
telemt_me_writer_close_signal_drop_total 123
telemt_me_writer_removed_unexpected_total 8754
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8441
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 4678521
telemt_user_connections_current{user="hello"} 3851
telemt_user_octets_from_client{user="hello"} 63129838186 (58.79 GB)
telemt_user_octets_to_client{user="hello"} 1546253790214 (1.41 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1354
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 8152.0 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519519
telemt_connections_bad_total 47313
telemt_connections_current 3248
telemt_connections_me_current 3248
telemt_handshake_timeouts_total 5974
telemt_upstream_connect_attempt_total 1557
telemt_upstream_connect_success_total 1557
telemt_upstream_connect_attempts_per_request{bucket="1"} 1557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1073
telemt_me_reconnect_success_total 1060
telemt_me_reader_eof_total 1067
telemt_me_idle_close_by_peer_total 1067
telemt_me_route_drop_no_conn_total 187938
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420610
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1804
telemt_desync_full_logged_total 593
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 623
telemt_desync_frames_bucket_total{bucket="gt_10"} 824
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 1052
telemt_me_writer_restored_same_endpoint_total 1060
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 420887
telemt_user_connections_current{user="hello"} 3248
telemt_user_octets_from_client{user="hello"} 6631825860 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 165418398095 (154.06 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1230
telemt_user_unique_ips_recent_window{user="hello"} 452
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 74788.0 (20h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5185004
telemt_connections_bad_total 628062
telemt_connections_current 5968
telemt_connections_me_current 5968
telemt_handshake_timeouts_total 76675
telemt_upstream_connect_attempt_total 13371
telemt_upstream_connect_success_total 13258
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 13370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 9033
telemt_me_reconnect_success_total 8061
telemt_me_reader_eof_total 8451
telemt_me_idle_close_by_peer_total 8446
telemt_me_route_drop_no_conn_total 3134813
telemt_me_route_drop_channel_closed_total 332
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3763588
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12974
telemt_desync_full_logged_total 4168
telemt_desync_suppressed_total 8806
telemt_desync_frames_bucket_total{bucket="1_2"} 3031
telemt_desync_frames_bucket_total{bucket="3_10"} 4852
telemt_desync_frames_bucket_total{bucket="gt_10"} 5091
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 389
telemt_me_writer_removed_unexpected_total 8176
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 8060
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 3769902
telemt_user_connections_current{user="hello"} 5968
telemt_user_octets_from_client{user="hello"} 57810700342 (53.84 GB)
telemt_user_octets_to_client{user="hello"} 1412379714956 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1821
telemt_user_unique_ips_recent_window{user="hello"} 747
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 74776.0 (20h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7376549
telemt_connections_bad_total 334043
telemt_connections_current 6853
telemt_connections_me_current 6853
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 98462
telemt_upstream_connect_attempt_total 83343
telemt_upstream_connect_success_total 71566
telemt_upstream_connect_fail_total 11777
telemt_upstream_connect_attempts_per_request{bucket="1"} 83343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11777
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 11627
telemt_me_reconnect_success_total 8472
telemt_me_reader_eof_total 8841
telemt_me_idle_close_by_peer_total 8839
telemt_me_route_drop_no_conn_total 11265303
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6382199
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
telemt_desync_total 15492
telemt_desync_full_logged_total 4498
telemt_desync_suppressed_total 10994
telemt_desync_frames_bucket_total{bucket="1_2"} 3425
telemt_desync_frames_bucket_total{bucket="3_10"} 6206
telemt_desync_frames_bucket_total{bucket="gt_10"} 5861
telemt_pool_swap_total 58
telemt_me_writer_close_signal_drop_total 845
telemt_me_writer_removed_unexpected_total 9328
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8468
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 856
telemt_user_connections_total{user="hello"} 6441607
telemt_user_connections_current{user="hello"} 6853
telemt_user_octets_from_client{user="hello"} 55943590687 (52.10 GB)
telemt_user_octets_to_client{user="hello"} 943238313053 (878.46 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1712
telemt_user_unique_ips_recent_window{user="hello"} 1080
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 12359.1 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2784305
telemt_connections_bad_total 238050
telemt_connections_current 5993
telemt_connections_me_current 5993
telemt_handshake_timeouts_total 31867
telemt_upstream_connect_attempt_total 2081
telemt_upstream_connect_success_total 2069
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 1423
telemt_me_reconnect_success_total 1415
telemt_me_reader_eof_total 1455
telemt_me_idle_close_by_peer_total 1454
telemt_me_route_drop_no_conn_total 4312023
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2342001
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5098
telemt_desync_full_logged_total 1453
telemt_desync_suppressed_total 3645
telemt_desync_frames_bucket_total{bucket="1_2"} 930
telemt_desync_frames_bucket_total{bucket="3_10"} 2079
telemt_desync_frames_bucket_total{bucket="gt_10"} 2089
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 1427
telemt_me_writer_restored_same_endpoint_total 1385
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 2336771
telemt_user_connections_current{user="hello"} 5993
telemt_user_octets_from_client{user="hello"} 19849908636 (18.49 GB)
telemt_user_octets_to_client{user="hello"} 293439443544 (273.29 GB)
telemt_user_unique_ips_current{user="hello"} 1915
telemt_user_unique_ips_recent_window{user="hello"} 803
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 1937.0 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47458
telemt_connections_bad_total 12855
telemt_connections_current 797
telemt_connections_me_current 797
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 811
telemt_upstream_connect_attempt_total 1871
telemt_upstream_connect_success_total 1860
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 336
telemt_me_reconnect_success_total 332
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 12865
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30833
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 20
telemt_me_writer_removed_unexpected_total 296
telemt_me_writer_restored_same_endpoint_total 330
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 32352
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 541729679 (516.63 MB)
telemt_user_octets_to_client{user="hello"} 5248596484 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 74740.6 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3898631
telemt_connections_bad_total 248279
telemt_connections_current 6317
telemt_connections_me_current 6317
telemt_handshake_timeouts_total 83831
telemt_upstream_connect_attempt_total 13084
telemt_upstream_connect_success_total 13001
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 13084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9358
telemt_me_reconnect_success_total 9292
telemt_me_reader_eof_total 9829
telemt_me_idle_close_by_peer_total 9828
telemt_me_route_drop_no_conn_total 1393780
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3286995
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15714
telemt_desync_full_logged_total 5234
telemt_desync_suppressed_total 10480
telemt_desync_frames_bucket_total{bucket="1_2"} 3220
telemt_desync_frames_bucket_total{bucket="3_10"} 5684
telemt_desync_frames_bucket_total{bucket="gt_10"} 6810
telemt_pool_swap_total 74
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 9433
telemt_me_writer_restored_same_endpoint_total 9275
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 3284910
telemt_user_connections_current{user="hello"} 6317
telemt_user_octets_from_client{user="hello"} 69711478968 (64.92 GB)
telemt_user_octets_to_client{user="hello"} 1665254574264 (1.51 TB)
telemt_user_unique_ips_current{user="hello"} 1993
telemt_user_unique_ips_recent_window{user="hello"} 818
```