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

# Server Metrics 2026-03-20 08:13:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 53766.7 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1170262
telemt_connections_bad_total 65120
telemt_connections_current 1947
telemt_connections_me_current 1947
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30925
telemt_upstream_connect_attempt_total 10304
telemt_upstream_connect_success_total 10193
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 10304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6467
telemt_me_reconnect_success_total 6417
telemt_me_reader_eof_total 6792
telemt_me_idle_close_by_peer_total 6790
telemt_me_route_drop_no_conn_total 340611
telemt_me_route_drop_channel_closed_total 167
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 965674
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4893
telemt_desync_full_logged_total 1760
telemt_desync_suppressed_total 3133
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1887
telemt_desync_frames_bucket_total{bucket="gt_10"} 2002
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 84
telemt_me_writer_removed_unexpected_total 6486
telemt_me_writer_restored_same_endpoint_total 6404
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 965181
telemt_user_connections_current{user="hello"} 1947
telemt_user_octets_from_client{user="hello"} 37831146468 (35.23 GB)
telemt_user_octets_to_client{user="hello"} 329568679465 (306.93 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 70222.4 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5190536
telemt_connections_bad_total 461156
telemt_connections_current 3756
telemt_connections_me_current 3756
telemt_handshake_timeouts_total 109687
telemt_upstream_connect_attempt_total 12957
telemt_upstream_connect_success_total 12689
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 12957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12272
telemt_me_reconnect_success_total 7994
telemt_me_reader_eof_total 8553
telemt_me_idle_close_by_peer_total 8552
telemt_me_route_drop_no_conn_total 3146197
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4284183
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15919
telemt_desync_full_logged_total 5275
telemt_desync_suppressed_total 10644
telemt_desync_frames_bucket_total{bucket="1_2"} 3165
telemt_desync_frames_bucket_total{bucket="3_10"} 6210
telemt_desync_frames_bucket_total{bucket="gt_10"} 6544
telemt_pool_swap_total 62
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 112
telemt_me_writer_removed_unexpected_total 8241
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7939
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 4286327
telemt_user_connections_current{user="hello"} 3756
telemt_user_octets_from_client{user="hello"} 57022852974 (53.11 GB)
telemt_user_octets_to_client{user="hello"} 1429297852994 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1315
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 3564.1 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177371
telemt_connections_bad_total 16653
telemt_connections_current 2626
telemt_connections_me_current 2626
telemt_handshake_timeouts_total 1836
telemt_upstream_connect_attempt_total 678
telemt_upstream_connect_success_total 678
telemt_upstream_connect_attempts_per_request{bucket="1"} 678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 434
telemt_me_reconnect_success_total 425
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 403
telemt_me_route_drop_no_conn_total 59904
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146921
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 644
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 414
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 408
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 147160
telemt_user_connections_current{user="hello"} 2626
telemt_user_octets_from_client{user="hello"} 2763567768 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 56646921619 (52.76 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1002
telemt_user_unique_ips_recent_window{user="hello"} 372
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 70199.8 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4583128
telemt_connections_bad_total 561485
telemt_connections_current 4936
telemt_connections_me_current 4936
telemt_handshake_timeouts_total 68633
telemt_upstream_connect_attempt_total 12716
telemt_upstream_connect_success_total 12610
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3086
telemt_me_reconnect_attempts_total 8639
telemt_me_reconnect_success_total 7674
telemt_me_reader_eof_total 8036
telemt_me_idle_close_by_peer_total 8031
telemt_me_route_drop_no_conn_total 2888131
telemt_me_route_drop_channel_closed_total 282
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3304826
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11603
telemt_desync_full_logged_total 3677
telemt_desync_suppressed_total 7926
telemt_desync_frames_bucket_total{bucket="1_2"} 2755
telemt_desync_frames_bucket_total{bucket="3_10"} 4401
telemt_desync_frames_bucket_total{bucket="gt_10"} 4447
telemt_pool_swap_total 69
telemt_me_writer_close_signal_drop_total 334
telemt_me_writer_removed_unexpected_total 7776
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7673
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 3311163
telemt_user_connections_current{user="hello"} 4936
telemt_user_octets_from_client{user="hello"} 48208349534 (44.90 GB)
telemt_user_octets_to_client{user="hello"} 1235796812676 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1576
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 70188.2 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5755563
telemt_connections_bad_total 307162
telemt_connections_current 5645
telemt_connections_me_current 5646
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 78899
telemt_upstream_connect_attempt_total 82621
telemt_upstream_connect_success_total 70883
telemt_upstream_connect_fail_total 11738
telemt_upstream_connect_attempts_per_request{bucket="1"} 82621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11738
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 11168
telemt_me_reconnect_success_total 8043
telemt_me_reader_eof_total 8375
telemt_me_idle_close_by_peer_total 8373
telemt_me_route_drop_no_conn_total 7688792
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4895969
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
telemt_desync_total 13947
telemt_desync_full_logged_total 4021
telemt_desync_suppressed_total 9926
telemt_desync_frames_bucket_total{bucket="1_2"} 3124
telemt_desync_frames_bucket_total{bucket="3_10"} 5566
telemt_desync_frames_bucket_total{bucket="gt_10"} 5257
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 829
telemt_me_writer_removed_unexpected_total 8875
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8039
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 832
telemt_user_connections_total{user="hello"} 4955185
telemt_user_connections_current{user="hello"} 5646
telemt_user_octets_from_client{user="hello"} 49955512703 (46.52 GB)
telemt_user_octets_to_client{user="hello"} 888588099313 (827.56 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1581
telemt_user_unique_ips_recent_window{user="hello"} 947
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 7771.3 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1599327
telemt_connections_bad_total 117445
telemt_connections_current 6025
telemt_connections_me_current 6025
telemt_handshake_timeouts_total 20947
telemt_upstream_connect_attempt_total 1325
telemt_upstream_connect_success_total 1317
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 893
telemt_me_reconnect_success_total 890
telemt_me_reader_eof_total 891
telemt_me_idle_close_by_peer_total 891
telemt_me_route_drop_no_conn_total 2447361
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1362451
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2962
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 2088
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 1183
telemt_desync_frames_bucket_total{bucket="gt_10"} 1212
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 892
telemt_me_writer_restored_same_endpoint_total 860
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 1362224
telemt_user_connections_current{user="hello"} 6025
telemt_user_octets_from_client{user="hello"} 13073596844 (12.18 GB)
telemt_user_octets_to_client{user="hello"} 189065179920 (176.08 GB)
telemt_user_unique_ips_current{user="hello"} 1806
telemt_user_unique_ips_recent_window{user="hello"} 812
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 7706.8 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121176
telemt_connections_bad_total 15075
telemt_connections_current 752
telemt_connections_me_current 752
telemt_handshake_timeouts_total 1502
telemt_upstream_connect_attempt_total 1381
telemt_upstream_connect_success_total 1369
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 952
telemt_me_reconnect_success_total 946
telemt_me_reader_eof_total 980
telemt_me_idle_close_by_peer_total 980
telemt_me_route_drop_no_conn_total 63458
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115013
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 365
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 955
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 97982
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 1424810024 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 38790525728 (36.13 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 70152.9 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3329324
telemt_connections_bad_total 218337
telemt_connections_current 5662
telemt_connections_me_current 5662
telemt_handshake_timeouts_total 62342
telemt_upstream_connect_attempt_total 12270
telemt_upstream_connect_success_total 12194
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8785
telemt_me_reconnect_success_total 8726
telemt_me_reader_eof_total 9222
telemt_me_idle_close_by_peer_total 9222
telemt_me_route_drop_no_conn_total 1140202
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2796742
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13698
telemt_desync_full_logged_total 4508
telemt_desync_suppressed_total 9190
telemt_desync_frames_bucket_total{bucket="1_2"} 2739
telemt_desync_frames_bucket_total{bucket="3_10"} 4903
telemt_desync_frames_bucket_total{bucket="gt_10"} 6056
telemt_pool_swap_total 71
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 8853
telemt_me_writer_restored_same_endpoint_total 8709
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 2794687
telemt_user_connections_current{user="hello"} 5662
telemt_user_octets_from_client{user="hello"} 59335262980 (55.26 GB)
telemt_user_octets_to_client{user="hello"} 1451289248604 (1.32 TB)
telemt_user_unique_ips_current{user="hello"} 1759
telemt_user_unique_ips_recent_window{user="hello"} 722
```