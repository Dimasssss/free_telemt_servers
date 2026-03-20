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

# Server Metrics 2026-03-20 09:25:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 58050.0 (16h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1347159
telemt_connections_bad_total 71905
telemt_connections_current 2070
telemt_connections_me_current 2070
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34816
telemt_upstream_connect_attempt_total 11104
telemt_upstream_connect_success_total 10987
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 11104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 7043
telemt_me_reconnect_success_total 6989
telemt_me_reader_eof_total 7397
telemt_me_idle_close_by_peer_total 7395
telemt_me_route_drop_no_conn_total 406002
telemt_me_route_drop_channel_closed_total 249
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1110051
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5848
telemt_desync_full_logged_total 2070
telemt_desync_suppressed_total 3778
telemt_desync_frames_bucket_total{bucket="1_2"} 1236
telemt_desync_frames_bucket_total{bucket="3_10"} 2262
telemt_desync_frames_bucket_total{bucket="gt_10"} 2350
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 130
telemt_me_writer_removed_unexpected_total 7062
telemt_me_writer_restored_same_endpoint_total 6976
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1109639
telemt_user_connections_current{user="hello"} 2070
telemt_user_octets_from_client{user="hello"} 40428919084 (37.65 GB)
telemt_user_octets_to_client{user="hello"} 377427728997 (351.51 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 74505.4 (20h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5650107
telemt_connections_bad_total 498639
telemt_connections_current 3905
telemt_connections_me_current 3905
telemt_handshake_timeouts_total 116645
telemt_upstream_connect_attempt_total 13683
telemt_upstream_connect_success_total 13390
telemt_upstream_connect_fail_total 293
telemt_upstream_connect_attempts_per_request{bucket="1"} 13683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 293
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12755
telemt_me_reconnect_success_total 8471
telemt_me_reader_eof_total 9061
telemt_me_idle_close_by_peer_total 9060
telemt_me_route_drop_no_conn_total 3533042
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4653317
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17119
telemt_desync_full_logged_total 5728
telemt_desync_suppressed_total 11391
telemt_desync_frames_bucket_total{bucket="1_2"} 3426
telemt_desync_frames_bucket_total{bucket="3_10"} 6712
telemt_desync_frames_bucket_total{bucket="gt_10"} 6981
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3394
telemt_me_writer_close_signal_drop_total 122
telemt_me_writer_removed_unexpected_total 8729
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8416
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 4655642
telemt_user_connections_current{user="hello"} 3905
telemt_user_octets_from_client{user="hello"} 62753100670 (58.44 GB)
telemt_user_octets_to_client{user="hello"} 1537519853906 (1.40 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1360
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 7847.4 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495772
telemt_connections_bad_total 45824
telemt_connections_current 3333
telemt_connections_me_current 3333
telemt_handshake_timeouts_total 5743
telemt_upstream_connect_attempt_total 1523
telemt_upstream_connect_success_total 1523
telemt_upstream_connect_attempts_per_request{bucket="1"} 1523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1059
telemt_me_reconnect_success_total 1046
telemt_me_reader_eof_total 1051
telemt_me_idle_close_by_peer_total 1051
telemt_me_route_drop_no_conn_total 175829
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400159
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1728
telemt_desync_full_logged_total 569
telemt_desync_suppressed_total 1159
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 1036
telemt_me_writer_restored_same_endpoint_total 1046
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 400431
telemt_user_connections_current{user="hello"} 3333
telemt_user_octets_from_client{user="hello"} 6378700624 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 158060508619 (147.21 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1215
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 74483.2 (20h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5142545
telemt_connections_bad_total 622910
telemt_connections_current 5553
telemt_connections_me_current 5553
telemt_handshake_timeouts_total 75960
telemt_upstream_connect_attempt_total 13320
telemt_upstream_connect_success_total 13208
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 13320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 9017
telemt_me_reconnect_success_total 8045
telemt_me_reader_eof_total 8432
telemt_me_idle_close_by_peer_total 8427
telemt_me_route_drop_no_conn_total 3117134
telemt_me_route_drop_channel_closed_total 329
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3732316
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12872
telemt_desync_full_logged_total 4136
telemt_desync_suppressed_total 8736
telemt_desync_frames_bucket_total{bucket="1_2"} 3011
telemt_desync_frames_bucket_total{bucket="3_10"} 4818
telemt_desync_frames_bucket_total{bucket="gt_10"} 5043
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 388
telemt_me_writer_removed_unexpected_total 8157
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 8044
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 3738643
telemt_user_connections_current{user="hello"} 5553
telemt_user_octets_from_client{user="hello"} 57433208658 (53.49 GB)
telemt_user_octets_to_client{user="hello"} 1397498575628 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1767
telemt_user_unique_ips_recent_window{user="hello"} 708
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 74471.2 (20h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7248529
telemt_connections_bad_total 331953
telemt_connections_current 5668
telemt_connections_me_current 5668
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 97059
telemt_upstream_connect_attempt_total 83300
telemt_upstream_connect_success_total 71525
telemt_upstream_connect_fail_total 11775
telemt_upstream_connect_attempts_per_request{bucket="1"} 83300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11775
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 172
telemt_me_reconnect_attempts_total 11614
telemt_me_reconnect_success_total 8460
telemt_me_reader_eof_total 8829
telemt_me_idle_close_by_peer_total 8827
telemt_me_route_drop_no_conn_total 10891643
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6263809
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
telemt_desync_total 15401
telemt_desync_full_logged_total 4465
telemt_desync_suppressed_total 10936
telemt_desync_frames_bucket_total{bucket="1_2"} 3405
telemt_desync_frames_bucket_total{bucket="3_10"} 6166
telemt_desync_frames_bucket_total{bucket="gt_10"} 5830
telemt_pool_swap_total 58
telemt_me_writer_close_signal_drop_total 845
telemt_me_writer_removed_unexpected_total 9316
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8456
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 856
telemt_user_connections_total{user="hello"} 6323219
telemt_user_connections_current{user="hello"} 5668
telemt_user_octets_from_client{user="hello"} 55427420455 (51.62 GB)
telemt_user_octets_to_client{user="hello"} 940249919377 (875.68 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1672
telemt_user_unique_ips_recent_window{user="hello"} 1076
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 12054.5 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2715859
telemt_connections_bad_total 228489
telemt_connections_current 6303
telemt_connections_me_current 6303
telemt_handshake_timeouts_total 31248
telemt_upstream_connect_attempt_total 2063
telemt_upstream_connect_success_total 2051
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 181
telemt_me_reconnect_attempts_total 1405
telemt_me_reconnect_success_total 1397
telemt_me_reader_eof_total 1437
telemt_me_idle_close_by_peer_total 1436
telemt_me_route_drop_no_conn_total 4204622
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2288933
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4990
telemt_desync_full_logged_total 1417
telemt_desync_suppressed_total 3573
telemt_desync_frames_bucket_total{bucket="1_2"} 908
telemt_desync_frames_bucket_total{bucket="3_10"} 2034
telemt_desync_frames_bucket_total{bucket="gt_10"} 2048
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 1409
telemt_me_writer_restored_same_endpoint_total 1367
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 2283693
telemt_user_connections_current{user="hello"} 6303
telemt_user_octets_from_client{user="hello"} 19363838888 (18.03 GB)
telemt_user_octets_to_client{user="hello"} 286255890032 (266.60 GB)
telemt_user_unique_ips_current{user="hello"} 1974
telemt_user_unique_ips_recent_window{user="hello"} 1076
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 1631.4 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42184
telemt_connections_bad_total 12622
telemt_connections_current 763
telemt_connections_me_current 763
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 572
telemt_upstream_connect_attempt_total 1801
telemt_upstream_connect_success_total 1792
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 311
telemt_me_reconnect_success_total 307
telemt_me_reader_eof_total 258
telemt_me_idle_close_by_peer_total 258
telemt_me_route_drop_no_conn_total 10999
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26207
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 20
telemt_me_writer_removed_unexpected_total 270
telemt_me_writer_restored_same_endpoint_total 305
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 27725
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 433776335 (413.68 MB)
telemt_user_octets_to_client{user="hello"} 4360450160 (4.06 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 74435.9 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3859793
telemt_connections_bad_total 247128
telemt_connections_current 6032
telemt_connections_me_current 6032
telemt_handshake_timeouts_total 82258
telemt_upstream_connect_attempt_total 13060
telemt_upstream_connect_success_total 12977
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 13060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9345
telemt_me_reconnect_success_total 9279
telemt_me_reader_eof_total 9816
telemt_me_idle_close_by_peer_total 9815
telemt_me_route_drop_no_conn_total 1382160
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3254128
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15505
telemt_desync_full_logged_total 5141
telemt_desync_suppressed_total 10364
telemt_desync_frames_bucket_total{bucket="1_2"} 3120
telemt_desync_frames_bucket_total{bucket="3_10"} 5621
telemt_desync_frames_bucket_total{bucket="gt_10"} 6764
telemt_pool_swap_total 74
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 9420
telemt_me_writer_restored_same_endpoint_total 9262
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 3252036
telemt_user_connections_current{user="hello"} 6032
telemt_user_octets_from_client{user="hello"} 68583494752 (63.87 GB)
telemt_user_octets_to_client{user="hello"} 1652071458088 (1.50 TB)
telemt_user_unique_ips_current{user="hello"} 1970
telemt_user_unique_ips_recent_window{user="hello"} 811
```