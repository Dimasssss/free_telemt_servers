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

# Server Metrics 2026-03-20 09:09:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 57135.0 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1306302
telemt_connections_bad_total 70462
telemt_connections_current 1974
telemt_connections_me_current 1974
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34003
telemt_upstream_connect_attempt_total 10966
telemt_upstream_connect_success_total 10852
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 10966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 6951
telemt_me_reconnect_success_total 6897
telemt_me_reader_eof_total 7298
telemt_me_idle_close_by_peer_total 7296
telemt_me_route_drop_no_conn_total 393709
telemt_me_route_drop_channel_closed_total 229
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1077938
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5557
telemt_desync_full_logged_total 1982
telemt_desync_suppressed_total 3575
telemt_desync_frames_bucket_total{bucket="1_2"} 1163
telemt_desync_frames_bucket_total{bucket="3_10"} 2158
telemt_desync_frames_bucket_total{bucket="gt_10"} 2236
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 126
telemt_me_writer_removed_unexpected_total 6970
telemt_me_writer_restored_same_endpoint_total 6884
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1077486
telemt_user_connections_current{user="hello"} 1974
telemt_user_octets_from_client{user="hello"} 39657028732 (36.93 GB)
telemt_user_octets_to_client{user="hello"} 366737499929 (341.55 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 73590.6 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5554463
telemt_connections_bad_total 483791
telemt_connections_current 3994
telemt_connections_me_current 3994
telemt_handshake_timeouts_total 115092
telemt_upstream_connect_attempt_total 13517
telemt_upstream_connect_success_total 13228
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 13517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12636
telemt_me_reconnect_success_total 8353
telemt_me_reader_eof_total 8939
telemt_me_idle_close_by_peer_total 8938
telemt_me_route_drop_no_conn_total 3502053
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4585662
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16784
telemt_desync_full_logged_total 5615
telemt_desync_suppressed_total 11169
telemt_desync_frames_bucket_total{bucket="1_2"} 3346
telemt_desync_frames_bucket_total{bucket="3_10"} 6566
telemt_desync_frames_bucket_total{bucket="gt_10"} 6872
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 589
telemt_me_writer_close_signal_drop_total 122
telemt_me_writer_removed_unexpected_total 8607
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8298
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 4587966
telemt_user_connections_current{user="hello"} 3994
telemt_user_octets_from_client{user="hello"} 61714607486 (57.48 GB)
telemt_user_octets_to_client{user="hello"} 1513699416970 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1385
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 6932.7 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415721
telemt_connections_bad_total 34704
telemt_connections_current 3022
telemt_connections_me_current 3022
telemt_handshake_timeouts_total 4963
telemt_upstream_connect_attempt_total 1399
telemt_upstream_connect_success_total 1399
telemt_upstream_connect_attempts_per_request{bucket="1"} 1399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 978
telemt_me_reconnect_success_total 965
telemt_me_reader_eof_total 964
telemt_me_idle_close_by_peer_total 964
telemt_me_route_drop_no_conn_total 143136
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340156
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1506
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 1004
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 514
telemt_desync_frames_bucket_total{bucket="gt_10"} 711
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_restored_same_endpoint_total 965
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 340397
telemt_user_connections_current{user="hello"} 3022
telemt_user_octets_from_client{user="hello"} 5498723408 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 134958197615 (125.69 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1158
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 73568.5 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5021101
telemt_connections_bad_total 604610
telemt_connections_current 5900
telemt_connections_me_current 5900
telemt_handshake_timeouts_total 73998
telemt_upstream_connect_attempt_total 13174
telemt_upstream_connect_success_total 13064
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 13174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 8917
telemt_me_reconnect_success_total 7947
telemt_me_reader_eof_total 8333
telemt_me_idle_close_by_peer_total 8328
telemt_me_route_drop_no_conn_total 3064609
telemt_me_route_drop_channel_closed_total 314
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3638729
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12548
telemt_desync_full_logged_total 4014
telemt_desync_suppressed_total 8534
telemt_desync_frames_bucket_total{bucket="1_2"} 2949
telemt_desync_frames_bucket_total{bucket="3_10"} 4713
telemt_desync_frames_bucket_total{bucket="gt_10"} 4886
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 377
telemt_me_writer_removed_unexpected_total 8056
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7946
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 3645082
telemt_user_connections_current{user="hello"} 5900
telemt_user_octets_from_client{user="hello"} 56356937038 (52.49 GB)
telemt_user_octets_to_client{user="hello"} 1358426400608 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1794
telemt_user_unique_ips_recent_window{user="hello"} 708
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 73556.8 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6924164
telemt_connections_bad_total 325258
telemt_connections_current 5597
telemt_connections_me_current 5597
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 92687
telemt_upstream_connect_attempt_total 83166
telemt_upstream_connect_success_total 71401
telemt_upstream_connect_fail_total 11765
telemt_upstream_connect_attempts_per_request{bucket="1"} 83166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11765
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11528
telemt_me_reconnect_success_total 8380
telemt_me_reader_eof_total 8735
telemt_me_idle_close_by_peer_total 8733
telemt_me_route_drop_no_conn_total 10261001
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5969342
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
telemt_desync_total 15075
telemt_desync_full_logged_total 4366
telemt_desync_suppressed_total 10709
telemt_desync_frames_bucket_total{bucket="1_2"} 3347
telemt_desync_frames_bucket_total{bucket="3_10"} 6044
telemt_desync_frames_bucket_total{bucket="gt_10"} 5684
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 844
telemt_me_writer_removed_unexpected_total 9229
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8376
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 849
telemt_user_connections_total{user="hello"} 6028773
telemt_user_connections_current{user="hello"} 5597
telemt_user_octets_from_client{user="hello"} 54003576811 (50.29 GB)
telemt_user_octets_to_client{user="hello"} 929484176921 (865.65 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1663
telemt_user_unique_ips_recent_window{user="hello"} 889
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 11139.7 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2447871
telemt_connections_bad_total 176857
telemt_connections_current 6147
telemt_connections_me_current 6147
telemt_handshake_timeouts_total 28799
telemt_upstream_connect_attempt_total 1927
telemt_upstream_connect_success_total 1915
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 1313
telemt_me_reconnect_success_total 1305
telemt_me_reader_eof_total 1336
telemt_me_idle_close_by_peer_total 1335
telemt_me_route_drop_no_conn_total 3840658
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2088662
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4475
telemt_desync_full_logged_total 1278
telemt_desync_suppressed_total 3197
telemt_desync_frames_bucket_total{bucket="1_2"} 816
telemt_desync_frames_bucket_total{bucket="3_10"} 1831
telemt_desync_frames_bucket_total{bucket="gt_10"} 1828
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 1314
telemt_me_writer_restored_same_endpoint_total 1275
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 2083450
telemt_user_connections_current{user="hello"} 6147
telemt_user_octets_from_client{user="hello"} 17624111292 (16.41 GB)
telemt_user_octets_to_client{user="hello"} 265837509480 (247.58 GB)
telemt_user_unique_ips_current{user="hello"} 1935
telemt_user_unique_ips_recent_window{user="hello"} 953
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 716.7 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21973
telemt_connections_bad_total 6722
telemt_connections_current 673
telemt_connections_me_current 673
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 262
telemt_upstream_connect_attempt_total 1666
telemt_upstream_connect_success_total 1664
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 226
telemt_me_reconnect_success_total 223
telemt_me_reader_eof_total 165
telemt_me_idle_close_by_peer_total 165
telemt_me_route_drop_no_conn_total 5335
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12856
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_writer_close_signal_drop_total 20
telemt_me_writer_removed_unexpected_total 184
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 14374
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 176918855 (168.72 MB)
telemt_user_octets_to_client{user="hello"} 2277809904 (2.12 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 73521.3 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3750754
telemt_connections_bad_total 242446
telemt_connections_current 5835
telemt_connections_me_current 5835
telemt_handshake_timeouts_total 77959
telemt_upstream_connect_attempt_total 12902
telemt_upstream_connect_success_total 12821
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 12902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9232
telemt_me_reconnect_success_total 9166
telemt_me_reader_eof_total 9685
telemt_me_idle_close_by_peer_total 9685
telemt_me_route_drop_no_conn_total 1346734
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3160597
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15108
telemt_desync_full_logged_total 5034
telemt_desync_suppressed_total 10074
telemt_desync_frames_bucket_total{bucket="1_2"} 2983
telemt_desync_frames_bucket_total{bucket="3_10"} 5494
telemt_desync_frames_bucket_total{bucket="gt_10"} 6631
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 55
telemt_me_writer_removed_unexpected_total 9303
telemt_me_writer_restored_same_endpoint_total 9149
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 3158538
telemt_user_connections_current{user="hello"} 5835
telemt_user_octets_from_client{user="hello"} 65006136392 (60.54 GB)
telemt_user_octets_to_client{user="hello"} 1610353324092 (1.46 TB)
telemt_user_unique_ips_current{user="hello"} 1903
telemt_user_unique_ips_recent_window{user="hello"} 729
```