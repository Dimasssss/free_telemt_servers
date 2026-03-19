# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

# Server Metrics 2026-03-19 08:21:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 37971.7 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 711067
telemt_connections_bad_total 73316
telemt_connections_current 1580
telemt_connections_me_current 1580
telemt_handshake_timeouts_total 25672
telemt_upstream_connect_attempt_total 7196
telemt_upstream_connect_success_total 7066
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 7196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6299
telemt_me_reconnect_success_total 5146
telemt_me_reader_eof_total 5463
telemt_me_idle_close_by_peer_total 5462
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 203054
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542921
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3542
telemt_desync_full_logged_total 1026
telemt_desync_suppressed_total 2516
telemt_desync_frames_bucket_total{bucket="1_2"} 1228
telemt_desync_frames_bucket_total{bucket="3_10"} 1320
telemt_desync_frames_bucket_total{bucket="gt_10"} 994
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5242
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5129
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 539942
telemt_user_connections_current{user="hello"} 1580
telemt_user_octets_from_client{user="hello"} 7501580376 (6.99 GB)
telemt_user_octets_to_client{user="hello"} 180850534124 (168.43 GB)
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 37975.7 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1727698
telemt_connections_bad_total 98563
telemt_connections_current 4083
telemt_connections_me_current 4083
telemt_handshake_timeouts_total 40383
telemt_upstream_connect_attempt_total 7188
telemt_upstream_connect_success_total 7053
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 7188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 6275
telemt_me_reconnect_success_total 5118
telemt_me_reader_eof_total 5428
telemt_me_idle_close_by_peer_total 5428
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 763013
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1426842
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6310
telemt_desync_full_logged_total 2119
telemt_desync_suppressed_total 4191
telemt_desync_frames_bucket_total{bucket="1_2"} 1132
telemt_desync_frames_bucket_total{bucket="3_10"} 2398
telemt_desync_frames_bucket_total{bucket="gt_10"} 2780
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5246
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5096
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 1426647
telemt_user_connections_current{user="hello"} 4083
telemt_user_octets_from_client{user="hello"} 24553634516 (22.87 GB)
telemt_user_octets_to_client{user="hello"} 547991167596 (510.36 GB)
telemt_user_unique_ips_current{user="hello"} 1397
telemt_user_unique_ips_recent_window{user="hello"} 630
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 37973.2 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1467862
telemt_connections_bad_total 192751
telemt_connections_current 3025
telemt_connections_me_current 3025
telemt_handshake_timeouts_total 36867
telemt_upstream_connect_attempt_total 6795
telemt_upstream_connect_success_total 6795
telemt_upstream_connect_attempts_per_request{bucket="1"} 6795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 4889
telemt_me_reconnect_success_total 4861
telemt_me_reader_eof_total 5153
telemt_me_idle_close_by_peer_total 5153
telemt_me_route_drop_no_conn_total 664298
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1123216
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5312
telemt_desync_full_logged_total 1637
telemt_desync_suppressed_total 3675
telemt_desync_frames_bucket_total{bucket="1_2"} 1141
telemt_desync_frames_bucket_total{bucket="3_10"} 1906
telemt_desync_frames_bucket_total{bucket="gt_10"} 2265
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 4951
telemt_me_writer_restored_same_endpoint_total 4845
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 1122806
telemt_user_connections_current{user="hello"} 3025
telemt_user_octets_from_client{user="hello"} 18872950708 (17.58 GB)
telemt_user_octets_to_client{user="hello"} 555494316064 (517.34 GB)
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 451
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 38026.1 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1541524
telemt_connections_bad_total 94095
telemt_connections_current 3235
telemt_connections_me_current 3235
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 38602
telemt_upstream_connect_attempt_total 15007
telemt_upstream_connect_success_total 14911
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 15007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7211
telemt_me_reconnect_success_total 4823
telemt_me_reader_eof_total 5129
telemt_me_idle_close_by_peer_total 5128
telemt_me_route_drop_no_conn_total 675005
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1094082
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3932
telemt_desync_full_logged_total 1352
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 770
telemt_desync_frames_bucket_total{bucket="3_10"} 1558
telemt_desync_frames_bucket_total{bucket="gt_10"} 1604
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5076
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 4799
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 1100944
telemt_user_connections_current{user="hello"} 3235
telemt_user_octets_from_client{user="hello"} 14242301488 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 348211239222 (324.30 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 979
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 37969.5 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1803800
telemt_connections_bad_total 468412
telemt_connections_current 3425
telemt_connections_me_current 3425
telemt_handshake_timeouts_total 37735
telemt_upstream_connect_attempt_total 6569
telemt_upstream_connect_success_total 6524
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 6569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 4631
telemt_me_reconnect_success_total 4598
telemt_me_reader_eof_total 4875
telemt_me_idle_close_by_peer_total 4875
telemt_me_route_drop_no_conn_total 468244
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1110729
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5392
telemt_desync_full_logged_total 1677
telemt_desync_suppressed_total 3715
telemt_desync_frames_bucket_total{bucket="1_2"} 1099
telemt_desync_frames_bucket_total{bucket="3_10"} 2434
telemt_desync_frames_bucket_total{bucket="gt_10"} 1859
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 4660
telemt_me_writer_restored_same_endpoint_total 4574
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1110376
telemt_user_connections_current{user="hello"} 3425
telemt_user_octets_from_client{user="hello"} 22514081440 (20.97 GB)
telemt_user_octets_to_client{user="hello"} 524978664688 (488.92 GB)
telemt_user_unique_ips_current{user="hello"} 1174
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 37981.9 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308424
telemt_connections_bad_total 14736
telemt_connections_current 943
telemt_connections_me_current 943
telemt_handshake_timeouts_total 2783
telemt_upstream_connect_attempt_total 9740
telemt_upstream_connect_success_total 9486
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 9740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 12936
telemt_me_reconnect_success_total 7559
telemt_me_reader_eof_total 8029
telemt_me_idle_close_by_peer_total 8029
telemt_me_route_drop_no_conn_total 142333
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275428
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 400
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 263
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7778
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7529
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 275391
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 4137574116 (3.85 GB)
telemt_user_octets_to_client{user="hello"} 124837019372 (116.26 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 37972.0 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1176224
telemt_connections_bad_total 97760
telemt_connections_current 3308
telemt_connections_me_current 3308
telemt_handshake_timeouts_total 51637
telemt_upstream_connect_attempt_total 7703
telemt_upstream_connect_success_total 7702
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7112
telemt_me_reconnect_success_total 5771
telemt_me_reader_eof_total 6122
telemt_me_idle_close_by_peer_total 6121
telemt_me_route_drop_no_conn_total 468368
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 981915
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5830
telemt_desync_full_logged_total 1920
telemt_desync_suppressed_total 3910
telemt_desync_frames_bucket_total{bucket="1_2"} 1123
telemt_desync_frames_bucket_total{bucket="3_10"} 2193
telemt_desync_frames_bucket_total{bucket="gt_10"} 2514
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5877
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5756
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 980888
telemt_user_connections_current{user="hello"} 3308
telemt_user_octets_from_client{user="hello"} 13805279184 (12.86 GB)
telemt_user_octets_to_client{user="hello"} 503569647044 (468.99 GB)
telemt_user_unique_ips_current{user="hello"} 1042
telemt_user_unique_ips_recent_window{user="hello"} 480
```