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

# Server Metrics 2026-03-20 09:35:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 58660.0 (16h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1376010
telemt_connections_bad_total 72879
telemt_connections_current 2053
telemt_connections_me_current 2053
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 35287
telemt_upstream_connect_attempt_total 11190
telemt_upstream_connect_success_total 11071
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 11190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 7082
telemt_me_reconnect_success_total 7027
telemt_me_reader_eof_total 7438
telemt_me_idle_close_by_peer_total 7436
telemt_me_route_drop_no_conn_total 413333
telemt_me_route_drop_channel_closed_total 254
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1131206
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6002
telemt_desync_full_logged_total 2116
telemt_desync_suppressed_total 3886
telemt_desync_frames_bucket_total{bucket="1_2"} 1286
telemt_desync_frames_bucket_total{bucket="3_10"} 2313
telemt_desync_frames_bucket_total{bucket="gt_10"} 2403
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 133
telemt_me_writer_removed_unexpected_total 7103
telemt_me_writer_restored_same_endpoint_total 7014
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1130874
telemt_user_connections_current{user="hello"} 2053
telemt_user_octets_from_client{user="hello"} 40860298612 (38.05 GB)
telemt_user_octets_to_client{user="hello"} 383988223797 (357.62 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 75115.5 (20h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5712392
telemt_connections_bad_total 508320
telemt_connections_current 3884
telemt_connections_me_current 3884
telemt_handshake_timeouts_total 117599
telemt_upstream_connect_attempt_total 13852
telemt_upstream_connect_success_total 13556
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 13852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12878
telemt_me_reconnect_success_total 8593
telemt_me_reader_eof_total 9182
telemt_me_idle_close_by_peer_total 9181
telemt_me_route_drop_no_conn_total 3552714
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4698626
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17311
telemt_desync_full_logged_total 5799
telemt_desync_suppressed_total 11512
telemt_desync_frames_bucket_total{bucket="1_2"} 3469
telemt_desync_frames_bucket_total{bucket="3_10"} 6787
telemt_desync_frames_bucket_total{bucket="gt_10"} 7055
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3394
telemt_me_writer_close_signal_drop_total 126
telemt_me_writer_removed_unexpected_total 8851
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8538
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 4700954
telemt_user_connections_current{user="hello"} 3884
telemt_user_octets_from_client{user="hello"} 63589141586 (59.22 GB)
telemt_user_octets_to_client{user="hello"} 1552841184186 (1.41 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1396
telemt_user_unique_ips_recent_window{user="hello"} 520
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 8457.9 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543711
telemt_connections_bad_total 49589
telemt_connections_current 3325
telemt_connections_me_current 3325
telemt_handshake_timeouts_total 6117
telemt_upstream_connect_attempt_total 1627
telemt_upstream_connect_success_total 1627
telemt_upstream_connect_attempts_per_request{bucket="1"} 1627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1120
telemt_me_reconnect_success_total 1107
telemt_me_reader_eof_total 1117
telemt_me_idle_close_by_peer_total 1117
telemt_me_route_drop_no_conn_total 197483
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440716
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1881
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1269
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 654
telemt_desync_frames_bucket_total{bucket="gt_10"} 850
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 1099
telemt_me_writer_restored_same_endpoint_total 1107
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 440989
telemt_user_connections_current{user="hello"} 3325
telemt_user_octets_from_client{user="hello"} 6942346760 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 173172147719 (161.28 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1270
telemt_user_unique_ips_recent_window{user="hello"} 478
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 75094.0 (20h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5226019
telemt_connections_bad_total 632181
telemt_connections_current 6229
telemt_connections_me_current 6229
telemt_handshake_timeouts_total 77431
telemt_upstream_connect_attempt_total 13419
telemt_upstream_connect_success_total 13307
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 13419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 9072
telemt_me_reconnect_success_total 8100
telemt_me_reader_eof_total 8494
telemt_me_idle_close_by_peer_total 8489
telemt_me_route_drop_no_conn_total 3154381
telemt_me_route_drop_channel_closed_total 336
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3797275
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13073
telemt_desync_full_logged_total 4197
telemt_desync_suppressed_total 8876
telemt_desync_frames_bucket_total{bucket="1_2"} 3047
telemt_desync_frames_bucket_total{bucket="3_10"} 4887
telemt_desync_frames_bucket_total{bucket="gt_10"} 5139
telemt_pool_swap_total 74
telemt_me_writer_close_signal_drop_total 394
telemt_me_writer_removed_unexpected_total 8215
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 8099
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 3803583
telemt_user_connections_current{user="hello"} 6229
telemt_user_octets_from_client{user="hello"} 58430372442 (54.42 GB)
telemt_user_octets_to_client{user="hello"} 1425693255988 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1849
telemt_user_unique_ips_recent_window{user="hello"} 784
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 75081.4 (20h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7501334
telemt_connections_bad_total 335608
telemt_connections_current 5711
telemt_connections_me_current 5711
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 99376
telemt_upstream_connect_attempt_total 83403
telemt_upstream_connect_success_total 71624
telemt_upstream_connect_fail_total 11779
telemt_upstream_connect_attempts_per_request{bucket="1"} 83403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11779
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 11672
telemt_me_reconnect_success_total 8515
telemt_me_reader_eof_total 8887
telemt_me_idle_close_by_peer_total 8885
telemt_me_route_drop_no_conn_total 11600698
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6495290
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
telemt_desync_total 15649
telemt_desync_full_logged_total 4543
telemt_desync_suppressed_total 11106
telemt_desync_frames_bucket_total{bucket="1_2"} 3460
telemt_desync_frames_bucket_total{bucket="3_10"} 6285
telemt_desync_frames_bucket_total{bucket="gt_10"} 5904
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 847
telemt_me_writer_removed_unexpected_total 9372
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8511
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 857
telemt_user_connections_total{user="hello"} 6554692
telemt_user_connections_current{user="hello"} 5711
telemt_user_octets_from_client{user="hello"} 56293823459 (52.43 GB)
telemt_user_octets_to_client{user="hello"} 946335272893 (881.34 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1690
telemt_user_unique_ips_recent_window{user="hello"} 1088
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 12664.6 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2829273
telemt_connections_bad_total 239859
telemt_connections_current 6212
telemt_connections_me_current 6212
telemt_handshake_timeouts_total 32468
telemt_upstream_connect_attempt_total 2124
telemt_upstream_connect_success_total 2111
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 1441
telemt_me_reconnect_success_total 1433
telemt_me_reader_eof_total 1475
telemt_me_idle_close_by_peer_total 1474
telemt_me_route_drop_no_conn_total 4343620
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2380846
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5191
telemt_desync_full_logged_total 1487
telemt_desync_suppressed_total 3704
telemt_desync_frames_bucket_total{bucket="1_2"} 949
telemt_desync_frames_bucket_total{bucket="3_10"} 2115
telemt_desync_frames_bucket_total{bucket="gt_10"} 2127
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 1447
telemt_me_writer_restored_same_endpoint_total 1403
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 2375631
telemt_user_connections_current{user="hello"} 6212
telemt_user_octets_from_client{user="hello"} 20289293932 (18.90 GB)
telemt_user_octets_to_client{user="hello"} 301326108296 (280.63 GB)
telemt_user_unique_ips_current{user="hello"} 1928
telemt_user_unique_ips_recent_window{user="hello"} 830
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 2242.0 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53049
telemt_connections_bad_total 13083
telemt_connections_current 773
telemt_connections_me_current 773
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 937
telemt_upstream_connect_attempt_total 1927
telemt_upstream_connect_success_total 1916
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 392
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 346
telemt_me_idle_close_by_peer_total 346
telemt_me_route_drop_no_conn_total 15511
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35932
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 80
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 21
telemt_me_writer_removed_unexpected_total 352
telemt_me_writer_restored_same_endpoint_total 386
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 37451
telemt_user_connections_current{user="hello"} 773
telemt_user_octets_from_client{user="hello"} 701074251 (668.60 MB)
telemt_user_octets_to_client{user="hello"} 6091313684 (5.67 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 75046.0 (20h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3936611
telemt_connections_bad_total 249314
telemt_connections_current 6412
telemt_connections_me_current 6412
telemt_handshake_timeouts_total 85359
telemt_upstream_connect_attempt_total 13155
telemt_upstream_connect_success_total 13071
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 13155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9396
telemt_me_reconnect_success_total 9329
telemt_me_reader_eof_total 9873
telemt_me_idle_close_by_peer_total 9872
telemt_me_route_drop_no_conn_total 1411074
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3320693
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15879
telemt_desync_full_logged_total 5280
telemt_desync_suppressed_total 10599
telemt_desync_frames_bucket_total{bucket="1_2"} 3282
telemt_desync_frames_bucket_total{bucket="3_10"} 5733
telemt_desync_frames_bucket_total{bucket="gt_10"} 6864
telemt_pool_swap_total 75
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 9473
telemt_me_writer_restored_same_endpoint_total 9312
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 3318596
telemt_user_connections_current{user="hello"} 6412
telemt_user_octets_from_client{user="hello"} 70807363208 (65.94 GB)
telemt_user_octets_to_client{user="hello"} 1679128368016 (1.53 TB)
telemt_user_unique_ips_current{user="hello"} 2022
telemt_user_unique_ips_recent_window{user="hello"} 822
```