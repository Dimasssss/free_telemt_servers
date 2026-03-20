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

# Server Metrics 2026-03-20 06:24:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 47228.6 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940525
telemt_connections_bad_total 58921
telemt_connections_current 1500
telemt_connections_me_current 1500
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24671
telemt_upstream_connect_attempt_total 9186
telemt_upstream_connect_success_total 9081
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 9186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5660
telemt_me_reconnect_success_total 5616
telemt_me_reader_eof_total 5951
telemt_me_idle_close_by_peer_total 5950
telemt_me_route_drop_no_conn_total 269884
telemt_me_route_drop_channel_closed_total 95
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763880
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4033
telemt_desync_full_logged_total 1455
telemt_desync_suppressed_total 2578
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 1570
telemt_desync_frames_bucket_total{bucket="gt_10"} 1681
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 5677
telemt_me_writer_restored_same_endpoint_total 5603
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 763264
telemt_user_connections_current{user="hello"} 1500
telemt_user_octets_from_client{user="hello"} 33799536800 (31.48 GB)
telemt_user_octets_to_client{user="hello"} 264741349933 (246.56 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 63684.5 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4127181
telemt_connections_bad_total 380549
telemt_connections_current 4951
telemt_connections_me_current 4951
telemt_handshake_timeouts_total 97098
telemt_upstream_connect_attempt_total 11977
telemt_upstream_connect_success_total 11756
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 11977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 11631
telemt_me_reconnect_success_total 7376
telemt_me_reader_eof_total 7880
telemt_me_idle_close_by_peer_total 7879
telemt_me_route_drop_no_conn_total 1852617
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3371531
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13545
telemt_desync_full_logged_total 4508
telemt_desync_suppressed_total 9037
telemt_desync_frames_bucket_total{bucket="1_2"} 2648
telemt_desync_frames_bucket_total{bucket="3_10"} 5270
telemt_desync_frames_bucket_total{bucket="gt_10"} 5627
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 7601
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7321
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 3371160
telemt_user_connections_current{user="hello"} 4951
telemt_user_octets_from_client{user="hello"} 49956425786 (46.53 GB)
telemt_user_octets_to_client{user="hello"} 1271632073618 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1651
telemt_user_unique_ips_recent_window{user="hello"} 681
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 63662.7 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3676781
telemt_connections_bad_total 508959
telemt_connections_current 3852
telemt_connections_me_current 3852
telemt_handshake_timeouts_total 55909
telemt_upstream_connect_attempt_total 10235
telemt_upstream_connect_success_total 10165
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 10235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7959
telemt_me_reconnect_success_total 7014
telemt_me_reader_eof_total 7392
telemt_me_idle_close_by_peer_total 7390
telemt_me_route_drop_no_conn_total 2165142
telemt_me_route_drop_channel_closed_total 210
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2600940
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9461
telemt_desync_full_logged_total 2970
telemt_desync_suppressed_total 6491
telemt_desync_frames_bucket_total{bucket="1_2"} 2363
telemt_desync_frames_bucket_total{bucket="3_10"} 3607
telemt_desync_frames_bucket_total{bucket="gt_10"} 3491
telemt_pool_swap_total 64
telemt_me_writer_close_signal_drop_total 87
telemt_me_writer_removed_unexpected_total 7093
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7013
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 2595928
telemt_user_connections_current{user="hello"} 3852
telemt_user_octets_from_client{user="hello"} 39063465620 (36.38 GB)
telemt_user_octets_to_client{user="hello"} 1057816988708 (985.17 GB)
telemt_user_unique_ips_current{user="hello"} 1280
telemt_user_unique_ips_recent_window{user="hello"} 511
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 63649.9 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3713369
telemt_connections_bad_total 261791
telemt_connections_current 4141
telemt_connections_me_current 4141
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 54420
telemt_upstream_connect_attempt_total 67631
telemt_upstream_connect_success_total 62906
telemt_upstream_connect_fail_total 4725
telemt_upstream_connect_attempts_per_request{bucket="1"} 67631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4725
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10328
telemt_me_reconnect_success_total 7348
telemt_me_reader_eof_total 7669
telemt_me_idle_close_by_peer_total 7668
telemt_me_route_drop_no_conn_total 3279884
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3049795
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10935
telemt_desync_full_logged_total 3357
telemt_desync_suppressed_total 7578
telemt_desync_frames_bucket_total{bucket="1_2"} 2561
telemt_desync_frames_bucket_total{bucket="3_10"} 4135
telemt_desync_frames_bucket_total{bucket="gt_10"} 4239
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 675
telemt_me_writer_removed_unexpected_total 8068
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7344
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 720
telemt_user_connections_total{user="hello"} 3100536
telemt_user_connections_current{user="hello"} 4141
telemt_user_octets_from_client{user="hello"} 43303273908 (40.33 GB)
telemt_user_octets_to_client{user="hello"} 816528093287 (760.45 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1271
telemt_user_unique_ips_recent_window{user="hello"} 648
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 1233.2 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157700
telemt_connections_bad_total 21545
telemt_connections_current 4347
telemt_connections_me_current 4347
telemt_handshake_timeouts_total 2884
telemt_upstream_connect_attempt_total 275
telemt_upstream_connect_success_total 274
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 160
telemt_me_reconnect_success_total 159
telemt_me_reader_eof_total 121
telemt_me_idle_close_by_peer_total 121
telemt_me_route_drop_no_conn_total 102553
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122125
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 340
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 143
telemt_me_writer_restored_same_endpoint_total 129
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 121982
telemt_user_connections_current{user="hello"} 4347
telemt_user_octets_from_client{user="hello"} 1630205712 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 32295474772 (30.08 GB)
telemt_user_unique_ips_current{user="hello"} 1394
telemt_user_unique_ips_recent_window{user="hello"} 522
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 1168.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17200
telemt_connections_bad_total 1391
telemt_connections_current 494
telemt_connections_me_current 494
telemt_handshake_timeouts_total 232
telemt_upstream_connect_attempt_total 177
telemt_upstream_connect_success_total 176
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 65
telemt_me_reconnect_success_total 65
telemt_me_reader_eof_total 43
telemt_me_idle_close_by_peer_total 43
telemt_me_route_drop_no_conn_total 10613
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19549
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 65
telemt_me_writer_restored_same_endpoint_total 57
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_user_connections_total{user="hello"} 14586
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 97583148 (93.06 MB)
telemt_user_octets_to_client{user="hello"} 4645631944 (4.33 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 63614.6 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2691928
telemt_connections_bad_total 171951
telemt_connections_current 3865
telemt_connections_me_current 3865
telemt_handshake_timeouts_total 47761
telemt_upstream_connect_attempt_total 11298
telemt_upstream_connect_success_total 11229
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8125
telemt_me_reconnect_success_total 8074
telemt_me_reader_eof_total 8534
telemt_me_idle_close_by_peer_total 8534
telemt_me_route_drop_no_conn_total 925351
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2252724
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11239
telemt_desync_full_logged_total 3693
telemt_desync_suppressed_total 7546
telemt_desync_frames_bucket_total{bucket="1_2"} 2204
telemt_desync_frames_bucket_total{bucket="3_10"} 3970
telemt_desync_frames_bucket_total{bucket="gt_10"} 5065
telemt_pool_swap_total 65
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 8185
telemt_me_writer_restored_same_endpoint_total 8057
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 2251583
telemt_user_connections_current{user="hello"} 3865
telemt_user_octets_from_client{user="hello"} 49328840668 (45.94 GB)
telemt_user_octets_to_client{user="hello"} 1185907980188 (1.08 TB)
telemt_user_unique_ips_current{user="hello"} 1245
telemt_user_unique_ips_recent_window{user="hello"} 464
```