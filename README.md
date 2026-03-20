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

# Server Metrics 2026-03-20 08:34:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 54985.7 (15h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1217791
telemt_connections_bad_total 66586
telemt_connections_current 1821
telemt_connections_me_current 1821
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32169
telemt_upstream_connect_attempt_total 10616
telemt_upstream_connect_success_total 10502
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 10616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 6695
telemt_me_reconnect_success_total 6644
telemt_me_reader_eof_total 7018
telemt_me_idle_close_by_peer_total 7016
telemt_me_route_drop_no_conn_total 357024
telemt_me_route_drop_channel_closed_total 181
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1005438
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5073
telemt_desync_full_logged_total 1828
telemt_desync_suppressed_total 3245
telemt_desync_frames_bucket_total{bucket="1_2"} 1041
telemt_desync_frames_bucket_total{bucket="3_10"} 1968
telemt_desync_frames_bucket_total{bucket="gt_10"} 2064
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 93
telemt_me_writer_removed_unexpected_total 6713
telemt_me_writer_restored_same_endpoint_total 6631
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1004970
telemt_user_connections_current{user="hello"} 1821
telemt_user_octets_from_client{user="hello"} 38442289652 (35.80 GB)
telemt_user_octets_to_client{user="hello"} 342831988593 (319.29 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 642
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 71441.6 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5300357
telemt_connections_bad_total 468871
telemt_connections_current 4307
telemt_connections_me_current 4307
telemt_handshake_timeouts_total 111513
telemt_upstream_connect_attempt_total 13205
telemt_upstream_connect_success_total 12925
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 13205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12422
telemt_me_reconnect_success_total 8142
telemt_me_reader_eof_total 8709
telemt_me_idle_close_by_peer_total 8708
telemt_me_route_drop_no_conn_total 3190348
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4373586
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16265
telemt_desync_full_logged_total 5396
telemt_desync_suppressed_total 10869
telemt_desync_frames_bucket_total{bucket="1_2"} 3250
telemt_desync_frames_bucket_total{bucket="3_10"} 6337
telemt_desync_frames_bucket_total{bucket="gt_10"} 6678
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 114
telemt_me_writer_removed_unexpected_total 8392
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8087
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 4375748
telemt_user_connections_current{user="hello"} 4307
telemt_user_octets_from_client{user="hello"} 58943983310 (54.90 GB)
telemt_user_octets_to_client{user="hello"} 1461805633398 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1469
telemt_user_unique_ips_recent_window{user="hello"} 557
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 4783.5 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262619
telemt_connections_bad_total 22356
telemt_connections_current 2760
telemt_connections_me_current 2760
telemt_handshake_timeouts_total 2819
telemt_upstream_connect_attempt_total 927
telemt_upstream_connect_success_total 927
telemt_upstream_connect_attempts_per_request{bucket="1"} 927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 595
telemt_me_reconnect_success_total 585
telemt_me_reader_eof_total 566
telemt_me_idle_close_by_peer_total 566
telemt_me_route_drop_no_conn_total 88075
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212196
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1017
telemt_desync_full_logged_total 338
telemt_desync_suppressed_total 679
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 570
telemt_me_writer_restored_same_endpoint_total 585
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 212449
telemt_user_connections_current{user="hello"} 2760
telemt_user_octets_from_client{user="hello"} 3454051584 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 85086430443 (79.24 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1001
telemt_user_unique_ips_recent_window{user="hello"} 404
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 71418.8 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4740050
telemt_connections_bad_total 573747
telemt_connections_current 5364
telemt_connections_me_current 5364
telemt_handshake_timeouts_total 70173
telemt_upstream_connect_attempt_total 12922
telemt_upstream_connect_success_total 12813
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 12922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3094
telemt_me_reconnect_attempts_total 8753
telemt_me_reconnect_success_total 7784
telemt_me_reader_eof_total 8156
telemt_me_idle_close_by_peer_total 8151
telemt_me_route_drop_no_conn_total 2940639
telemt_me_route_drop_channel_closed_total 297
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3418281
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11901
telemt_desync_full_logged_total 3791
telemt_desync_suppressed_total 8110
telemt_desync_frames_bucket_total{bucket="1_2"} 2808
telemt_desync_frames_bucket_total{bucket="3_10"} 4503
telemt_desync_frames_bucket_total{bucket="gt_10"} 4590
telemt_pool_swap_total 71
telemt_me_writer_close_signal_drop_total 353
telemt_me_writer_removed_unexpected_total 7889
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7783
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 3424634
telemt_user_connections_current{user="hello"} 5364
telemt_user_octets_from_client{user="hello"} 50263903458 (46.81 GB)
telemt_user_octets_to_client{user="hello"} 1282982195596 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1680
telemt_user_unique_ips_recent_window{user="hello"} 708
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 71407.1 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6225989
telemt_connections_bad_total 313175
telemt_connections_current 5256
telemt_connections_me_current 5256
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 84430
telemt_upstream_connect_attempt_total 82845
telemt_upstream_connect_success_total 71092
telemt_upstream_connect_fail_total 11753
telemt_upstream_connect_attempts_per_request{bucket="1"} 82845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11753
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11300
telemt_me_reconnect_success_total 8165
telemt_me_reader_eof_total 8508
telemt_me_idle_close_by_peer_total 8506
telemt_me_route_drop_no_conn_total 8692407
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5333532
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
telemt_desync_total 14408
telemt_desync_full_logged_total 4150
telemt_desync_suppressed_total 10258
telemt_desync_frames_bucket_total{bucket="1_2"} 3238
telemt_desync_frames_bucket_total{bucket="3_10"} 5761
telemt_desync_frames_bucket_total{bucket="gt_10"} 5409
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 830
telemt_me_writer_removed_unexpected_total 9005
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8161
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 840
telemt_user_connections_total{user="hello"} 5392809
telemt_user_connections_current{user="hello"} 5256
telemt_user_octets_from_client{user="hello"} 51103319599 (47.59 GB)
telemt_user_octets_to_client{user="hello"} 903375196197 (841.33 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1543
telemt_user_unique_ips_recent_window{user="hello"} 918
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 8990.1 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1952090
telemt_connections_bad_total 134468
telemt_connections_current 6100
telemt_connections_me_current 6100
telemt_handshake_timeouts_total 23850
telemt_upstream_connect_attempt_total 1504
telemt_upstream_connect_success_total 1495
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 1028
telemt_me_reconnect_success_total 1025
telemt_me_reader_eof_total 1042
telemt_me_idle_close_by_peer_total 1041
telemt_me_route_drop_no_conn_total 3085137
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1668616
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3527
telemt_desync_full_logged_total 1018
telemt_desync_suppressed_total 2509
telemt_desync_frames_bucket_total{bucket="1_2"} 664
telemt_desync_frames_bucket_total{bucket="3_10"} 1431
telemt_desync_frames_bucket_total{bucket="gt_10"} 1432
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 1030
telemt_me_writer_restored_same_endpoint_total 995
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1663439
telemt_user_connections_current{user="hello"} 6100
telemt_user_octets_from_client{user="hello"} 14976018224 (13.95 GB)
telemt_user_octets_to_client{user="hello"} 213757007800 (199.08 GB)
telemt_user_unique_ips_current{user="hello"} 1852
telemt_user_unique_ips_recent_window{user="hello"} 871
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 8925.6 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139225
telemt_connections_bad_total 16645
telemt_connections_current 743
telemt_connections_me_current 743
telemt_handshake_timeouts_total 1648
telemt_upstream_connect_attempt_total 1552
telemt_upstream_connect_success_total 1539
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1079
telemt_me_reconnect_success_total 1071
telemt_me_reader_eof_total 1115
telemt_me_idle_close_by_peer_total 1115
telemt_me_route_drop_no_conn_total 73021
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131684
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 424
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 283
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 1084
telemt_me_writer_restored_same_endpoint_total 1063
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 113680
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 1657591544 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 44829643700 (41.75 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 71371.8 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3466892
telemt_connections_bad_total 224747
telemt_connections_current 5870
telemt_connections_me_current 5870
telemt_handshake_timeouts_total 68464
telemt_upstream_connect_attempt_total 12489
telemt_upstream_connect_success_total 12410
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 12489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8913
telemt_me_reconnect_success_total 8853
telemt_me_reader_eof_total 9366
telemt_me_idle_close_by_peer_total 9366
telemt_me_route_drop_no_conn_total 1190244
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2915443
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14237
telemt_desync_full_logged_total 4728
telemt_desync_suppressed_total 9509
telemt_desync_frames_bucket_total{bucket="1_2"} 2820
telemt_desync_frames_bucket_total{bucket="3_10"} 5121
telemt_desync_frames_bucket_total{bucket="gt_10"} 6296
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 8983
telemt_me_writer_restored_same_endpoint_total 8836
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 2913415
telemt_user_connections_current{user="hello"} 5870
telemt_user_octets_from_client{user="hello"} 61864565152 (57.62 GB)
telemt_user_octets_to_client{user="hello"} 1511570417452 (1.37 TB)
telemt_user_unique_ips_current{user="hello"} 1819
telemt_user_unique_ips_recent_window{user="hello"} 725
```