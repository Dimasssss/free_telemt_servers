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

# Server Metrics 2026-03-20 07:42:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 51922.6 (14h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1103132
telemt_connections_bad_total 64393
telemt_connections_current 1678
telemt_connections_me_current 1678
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 28347
telemt_upstream_connect_attempt_total 10013
telemt_upstream_connect_success_total 9904
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 10013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6265
telemt_me_reconnect_success_total 6218
telemt_me_reader_eof_total 6583
telemt_me_idle_close_by_peer_total 6582
telemt_me_route_drop_no_conn_total 319478
telemt_me_route_drop_channel_closed_total 150
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 907065
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4612
telemt_desync_full_logged_total 1660
telemt_desync_suppressed_total 2952
telemt_desync_frames_bucket_total{bucket="1_2"} 934
telemt_desync_frames_bucket_total{bucket="3_10"} 1780
telemt_desync_frames_bucket_total{bucket="gt_10"} 1898
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 75
telemt_me_writer_removed_unexpected_total 6286
telemt_me_writer_restored_same_endpoint_total 6205
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 906501
telemt_user_connections_current{user="hello"} 1678
telemt_user_octets_from_client{user="hello"} 36086876244 (33.61 GB)
telemt_user_octets_to_client{user="hello"} 311748529521 (290.34 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 579
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 68378.2 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5037750
telemt_connections_bad_total 446889
telemt_connections_current 3620
telemt_connections_me_current 3620
telemt_handshake_timeouts_total 107096
telemt_upstream_connect_attempt_total 12670
telemt_upstream_connect_success_total 12409
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 12670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12078
telemt_me_reconnect_success_total 7803
telemt_me_reader_eof_total 8351
telemt_me_idle_close_by_peer_total 8350
telemt_me_route_drop_no_conn_total 3093167
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4159667
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15404
telemt_desync_full_logged_total 5084
telemt_desync_suppressed_total 10320
telemt_desync_frames_bucket_total{bucket="1_2"} 3030
telemt_desync_frames_bucket_total{bucket="3_10"} 6013
telemt_desync_frames_bucket_total{bucket="gt_10"} 6361
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 109
telemt_me_writer_removed_unexpected_total 8048
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7748
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 4161608
telemt_user_connections_current{user="hello"} 3620
telemt_user_octets_from_client{user="hello"} 55544265110 (51.73 GB)
telemt_user_octets_to_client{user="hello"} 1382993086178 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1289
telemt_user_unique_ips_recent_window{user="hello"} 471
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 1720.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62409
telemt_connections_bad_total 4978
telemt_connections_current 2161
telemt_connections_me_current 2161
telemt_handshake_timeouts_total 561
telemt_upstream_connect_attempt_total 393
telemt_upstream_connect_success_total 393
telemt_upstream_connect_attempts_per_request{bucket="1"} 393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 235
telemt_me_reconnect_success_total 232
telemt_me_reader_eof_total 197
telemt_me_idle_close_by_peer_total 197
telemt_me_route_drop_no_conn_total 21495
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53818
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 212
telemt_me_writer_restored_same_endpoint_total 232
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 53891
telemt_user_connections_current{user="hello"} 2161
telemt_user_octets_from_client{user="hello"} 1021880600 (974.54 MB)
telemt_user_octets_to_client{user="hello"} 19673264291 (18.32 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 822
telemt_user_unique_ips_recent_window{user="hello"} 352
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 68356.4 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4353654
telemt_connections_bad_total 550227
telemt_connections_current 4571
telemt_connections_me_current 4571
telemt_handshake_timeouts_total 66152
telemt_upstream_connect_attempt_total 12475
telemt_upstream_connect_success_total 12369
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5690
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3086
telemt_me_reconnect_attempts_total 8487
telemt_me_reconnect_success_total 7523
telemt_me_reader_eof_total 7872
telemt_me_idle_close_by_peer_total 7867
telemt_me_route_drop_no_conn_total 2817662
telemt_me_route_drop_channel_closed_total 271
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3134746
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11096
telemt_desync_full_logged_total 3490
telemt_desync_suppressed_total 7606
telemt_desync_frames_bucket_total{bucket="1_2"} 2647
telemt_desync_frames_bucket_total{bucket="3_10"} 4229
telemt_desync_frames_bucket_total{bucket="gt_10"} 4220
telemt_pool_swap_total 67
telemt_me_writer_close_signal_drop_total 321
telemt_me_writer_removed_unexpected_total 7621
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7522
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 3141124
telemt_user_connections_current{user="hello"} 4571
telemt_user_octets_from_client{user="hello"} 43820839738 (40.81 GB)
telemt_user_octets_to_client{user="hello"} 1175835136224 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1448
telemt_user_unique_ips_recent_window{user="hello"} 629
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 68344.4 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5100177
telemt_connections_bad_total 297532
telemt_connections_current 6721
telemt_connections_me_current 6721
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 70698
telemt_upstream_connect_attempt_total 72098
telemt_upstream_connect_success_total 67176
telemt_upstream_connect_fail_total 4922
telemt_upstream_connect_attempts_per_request{bucket="1"} 72098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 732
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4922
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 131
telemt_me_reconnect_attempts_total 10907
telemt_me_reconnect_success_total 7855
telemt_me_reader_eof_total 8195
telemt_me_idle_close_by_peer_total 8194
telemt_me_route_drop_no_conn_total 6416957
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4309743
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13413
telemt_desync_full_logged_total 3872
telemt_desync_suppressed_total 9541
telemt_desync_frames_bucket_total{bucket="1_2"} 2991
telemt_desync_frames_bucket_total{bucket="3_10"} 5318
telemt_desync_frames_bucket_total{bucket="gt_10"} 5104
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 822
telemt_me_writer_removed_unexpected_total 8698
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7851
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 843
telemt_user_connections_total{user="hello"} 4364719
telemt_user_connections_current{user="hello"} 6721
telemt_user_octets_from_client{user="hello"} 48013619218 (44.72 GB)
telemt_user_octets_to_client{user="hello"} 867974138186 (808.36 GB)
telemt_user_msgs_from_client{user="hello"} 265792
telemt_user_msgs_to_client{user="hello"} 1786810
telemt_user_unique_ips_current{user="hello"} 1476
telemt_user_unique_ips_recent_window{user="hello"} 1081
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 5927.1 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1052720
telemt_connections_bad_total 92685
telemt_connections_current 5526
telemt_connections_me_current 5526
telemt_handshake_timeouts_total 17183
telemt_upstream_connect_attempt_total 958
telemt_upstream_connect_success_total 954
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 622
telemt_me_reconnect_success_total 620
telemt_me_reader_eof_total 615
telemt_me_idle_close_by_peer_total 615
telemt_me_route_drop_no_conn_total 1370231
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 881930
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2200
telemt_desync_full_logged_total 668
telemt_desync_suppressed_total 1532
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 893
telemt_desync_frames_bucket_total{bucket="gt_10"} 873
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 616
telemt_me_writer_restored_same_endpoint_total 590
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 881863
telemt_user_connections_current{user="hello"} 5526
telemt_user_octets_from_client{user="hello"} 10152842416 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 148365442136 (138.18 GB)
telemt_user_unique_ips_current{user="hello"} 1674
telemt_user_unique_ips_recent_window{user="hello"} 1013
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 5862.5 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92169
telemt_connections_bad_total 13800
telemt_connections_current 672
telemt_connections_me_current 672
telemt_handshake_timeouts_total 955
telemt_upstream_connect_attempt_total 1077
telemt_upstream_connect_success_total 1068
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 738
telemt_me_reconnect_success_total 733
telemt_me_reader_eof_total 748
telemt_me_idle_close_by_peer_total 748
telemt_me_route_drop_no_conn_total 47465
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88612
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 276
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 738
telemt_me_writer_restored_same_endpoint_total 725
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 73416
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 1126085836 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 29466878820 (27.44 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 68308.8 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3129519
telemt_connections_bad_total 209723
telemt_connections_current 5237
telemt_connections_me_current 5237
telemt_handshake_timeouts_total 56236
telemt_upstream_connect_attempt_total 11950
telemt_upstream_connect_success_total 11875
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 11950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8553
telemt_me_reconnect_success_total 8497
telemt_me_reader_eof_total 8985
telemt_me_idle_close_by_peer_total 8985
telemt_me_route_drop_no_conn_total 1064330
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2623850
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12923
telemt_desync_full_logged_total 4200
telemt_desync_suppressed_total 8723
telemt_desync_frames_bucket_total{bucket="1_2"} 2568
telemt_desync_frames_bucket_total{bucket="3_10"} 4603
telemt_desync_frames_bucket_total{bucket="gt_10"} 5752
telemt_pool_swap_total 70
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8619
telemt_me_writer_restored_same_endpoint_total 8480
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 2621737
telemt_user_connections_current{user="hello"} 5237
telemt_user_octets_from_client{user="hello"} 55677050500 (51.85 GB)
telemt_user_octets_to_client{user="hello"} 1370717103448 (1.25 TB)
telemt_user_unique_ips_current{user="hello"} 1592
telemt_user_unique_ips_recent_window{user="hello"} 630
```