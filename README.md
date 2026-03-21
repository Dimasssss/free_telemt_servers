# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
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

## rdp-onedash.ru (2 сервера)
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

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-21 13:51:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 62140.7 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2065076
telemt_connections_bad_total 103044
telemt_connections_current 1708
telemt_connections_me_current 1708
telemt_handshake_timeouts_total 73847
telemt_upstream_connect_attempt_total 23793
telemt_upstream_connect_success_total 23673
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 23750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15254
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1341
telemt_me_reconnect_success_total 559
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 1534958
telemt_me_route_drop_channel_closed_total 513
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1632616
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 436
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 487
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 50
telemt_me_writers_warm_current 5
telemt_desync_total 6476
telemt_desync_full_logged_total 2236
telemt_desync_suppressed_total 4240
telemt_desync_frames_bucket_total{bucket="1_2"} 1456
telemt_desync_frames_bucket_total{bucket="3_10"} 2449
telemt_desync_frames_bucket_total{bucket="gt_10"} 2571
telemt_pool_swap_total 67
telemt_pool_force_close_total 2004
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 385
telemt_me_draining_writers_reap_progress_total 21266
telemt_me_writer_removed_unexpected_total 513
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1754
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19847
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1929
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 75
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19262
telemt_me_writer_teardown_success_total{mode="normal"} 21601
telemt_me_writer_teardown_noop_total 21271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42872
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 170.094155
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42872
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 385
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 483
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1631377
telemt_user_connections_current{user="hello"} 1708
telemt_user_octets_from_client{user="hello"} 24351271539 (22.68 GB)
telemt_user_octets_to_client{user="hello"} 424742825623 (395.57 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 627
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1693.9 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166588
telemt_connections_bad_total 5812
telemt_connections_current 2970
telemt_connections_me_current 2970
telemt_handshake_timeouts_total 5095
telemt_upstream_connect_attempt_total 552
telemt_upstream_connect_success_total 551
telemt_upstream_connect_attempts_per_request{bucket="1"} 551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 81737
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145424
telemt_me_endpoint_quarantine_total 14
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 551
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 346
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 1
telemt_pool_force_close_total 21
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 426
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 410
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 405
telemt_me_writer_teardown_success_total{mode="normal"} 435
telemt_me_writer_teardown_noop_total 426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 861
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.051921
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 861
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 144386
telemt_user_connections_current{user="hello"} 2970
telemt_user_octets_from_client{user="hello"} 3105749656 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 34995097956 (32.59 GB)
telemt_user_unique_ips_current{user="hello"} 1420
telemt_user_unique_ips_recent_window{user="hello"} 552
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 62138.4 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4109187
telemt_connections_bad_total 396075
telemt_connections_current 4654
telemt_connections_me_current 4654
telemt_handshake_timeouts_total 158539
telemt_upstream_connect_attempt_total 23540
telemt_upstream_connect_success_total 23500
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 903
telemt_me_reconnect_success_total 530
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 2078645
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3320871
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 12
telemt_desync_total 14004
telemt_desync_full_logged_total 4730
telemt_desync_suppressed_total 9274
telemt_desync_frames_bucket_total{bucket="1_2"} 2961
telemt_desync_frames_bucket_total{bucket="3_10"} 5518
telemt_desync_frames_bucket_total{bucket="gt_10"} 5525
telemt_pool_swap_total 65
telemt_pool_force_close_total 2078
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 319
telemt_me_draining_writers_reap_progress_total 21355
telemt_me_writer_removed_unexpected_total 510
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1849
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19826
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19277
telemt_me_writer_teardown_success_total{mode="normal"} 21675
telemt_me_writer_teardown_noop_total 21373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43048
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 65.976351
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43048
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 319
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 482
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 3316759
telemt_user_connections_current{user="hello"} 4654
telemt_user_octets_from_client{user="hello"} 54964337216 (51.19 GB)
telemt_user_octets_to_client{user="hello"} 1139067231984 (1.04 TB)
telemt_user_unique_ips_current{user="hello"} 1764
telemt_user_unique_ips_recent_window{user="hello"} 633
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 62139.6 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3363356
telemt_connections_bad_total 373646
telemt_connections_current 3945
telemt_connections_me_current 3945
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 125887
telemt_upstream_connect_attempt_total 27886
telemt_upstream_connect_success_total 27611
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 27746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 477
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1165
telemt_me_reconnect_success_total 549
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 1051065
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2433310
telemt_me_endpoint_quarantine_total 401
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 473
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 10
telemt_desync_total 11124
telemt_desync_full_logged_total 3768
telemt_desync_suppressed_total 7356
telemt_desync_frames_bucket_total{bucket="1_2"} 2785
telemt_desync_frames_bucket_total{bucket="3_10"} 4276
telemt_desync_frames_bucket_total{bucket="gt_10"} 4063
telemt_pool_swap_total 67
telemt_pool_force_close_total 1906
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 20541
telemt_me_writer_removed_unexpected_total 499
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1740
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19306
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1780
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 126
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18635
telemt_me_writer_teardown_success_total{mode="normal"} 21046
telemt_me_writer_teardown_noop_total 20542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41588
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.008604
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41588
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 463
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 2433842
telemt_user_connections_current{user="hello"} 3945
telemt_user_octets_from_client{user="hello"} 45539208353 (42.41 GB)
telemt_user_octets_to_client{user="hello"} 1143973057915 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1535
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 62103.4 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3274965
telemt_connections_bad_total 350629
telemt_connections_current 3241
telemt_connections_me_current 3241
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 94550
telemt_upstream_connect_attempt_total 33049
telemt_upstream_connect_success_total 32821
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 845
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1281
telemt_me_reconnect_success_total 621
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 1005941
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2396263
telemt_me_endpoint_quarantine_total 449
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 462
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 11200
telemt_desync_full_logged_total 3714
telemt_desync_suppressed_total 7486
telemt_desync_frames_bucket_total{bucket="1_2"} 2839
telemt_desync_frames_bucket_total{bucket="3_10"} 4216
telemt_desync_frames_bucket_total{bucket="gt_10"} 4145
telemt_pool_swap_total 65
telemt_pool_force_close_total 1845
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 21864
telemt_me_writer_removed_unexpected_total 538
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1839
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20598
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1678
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 167
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20019
telemt_me_writer_teardown_success_total{mode="normal"} 22437
telemt_me_writer_teardown_noop_total 21869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44306
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.327549
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44306
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2400995
telemt_user_connections_current{user="hello"} 3241
telemt_user_octets_from_client{user="hello"} 52669599385 (49.05 GB)
telemt_user_octets_to_client{user="hello"} 1139786077252 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1378
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 62142.9 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11167483
telemt_connections_bad_total 763629
telemt_connections_current 6243
telemt_connections_me_current 6243
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 351555
telemt_upstream_connect_attempt_total 111087
telemt_upstream_connect_success_total 101934
telemt_upstream_connect_fail_total 8199
telemt_upstream_connect_attempts_per_request{bucket="1"} 110133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5007
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8199
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3623
telemt_me_reconnect_success_total 1264
telemt_me_reader_eof_total 918
telemt_me_idle_close_by_peer_total 917
telemt_me_route_drop_no_conn_total 20756730
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9152809
telemt_me_endpoint_quarantine_total 465
telemt_me_single_endpoint_outage_enter_total 68
telemt_me_single_endpoint_outage_exit_total 68
telemt_me_single_endpoint_outage_reconnect_attempt_total 153
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 153
telemt_me_single_endpoint_shadow_rotate_total 486
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 14
telemt_desync_total 16896
telemt_desync_full_logged_total 5389
telemt_desync_suppressed_total 11507
telemt_desync_frames_bucket_total{bucket="1_2"} 3645
telemt_desync_frames_bucket_total{bucket="3_10"} 7394
telemt_desync_frames_bucket_total{bucket="gt_10"} 5857
telemt_pool_swap_total 62
telemt_pool_force_close_total 2020
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 20195
telemt_me_writer_removed_unexpected_total 1228
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2625
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18626
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1686
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18175
telemt_me_writer_teardown_success_total{mode="normal"} 21251
telemt_me_writer_teardown_noop_total 20205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41456
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 161.526116
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41456
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 896
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 9226926
telemt_user_connections_current{user="hello"} 6243
telemt_user_octets_from_client{user="hello"} 69159321313 (64.41 GB)
telemt_user_octets_to_client{user="hello"} 735823789298 (685.29 GB)
telemt_user_msgs_from_client{user="hello"} 227549
telemt_user_msgs_to_client{user="hello"} 539047
telemt_user_unique_ips_current{user="hello"} 1964
telemt_user_unique_ips_recent_window{user="hello"} 1193
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 62110.5 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3289168
telemt_connections_bad_total 373370
telemt_connections_current 3649
telemt_connections_me_current 3649
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 72932
telemt_upstream_connect_attempt_total 26727
telemt_upstream_connect_success_total 26441
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 26696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2579
telemt_me_reconnect_success_total 949
telemt_me_reader_eof_total 942
telemt_me_idle_close_by_peer_total 942
telemt_me_route_drop_no_conn_total 1294850
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2515650
telemt_me_endpoint_quarantine_total 385
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 467
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 89
telemt_desync_total 11831
telemt_desync_full_logged_total 4112
telemt_desync_suppressed_total 7719
telemt_desync_frames_bucket_total{bucket="1_2"} 2287
telemt_desync_frames_bucket_total{bucket="3_10"} 4714
telemt_desync_frames_bucket_total{bucket="gt_10"} 4830
telemt_pool_swap_total 61
telemt_pool_force_close_total 1741
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 166
telemt_me_draining_writers_reap_progress_total 22316
telemt_me_writer_removed_unexpected_total 913
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2191
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21068
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1527
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 214
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20575
telemt_me_writer_teardown_success_total{mode="normal"} 23259
telemt_me_writer_teardown_noop_total 22317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.834532
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 166
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 814
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 2500303
telemt_user_connections_current{user="hello"} 3649
telemt_user_octets_from_client{user="hello"} 53233388308 (49.58 GB)
telemt_user_octets_to_client{user="hello"} 1082064171742 (1007.75 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1555
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 62105.0 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5049453
telemt_connections_bad_total 245787
telemt_connections_current 3303
telemt_connections_me_current 3303
telemt_handshake_timeouts_total 2233254
telemt_upstream_connect_attempt_total 24476
telemt_upstream_connect_success_total 24442
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 290
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1056
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 455
telemt_me_idle_close_by_peer_total 455
telemt_me_route_drop_no_conn_total 1175809
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2271965
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 480
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 10850
telemt_desync_full_logged_total 3817
telemt_desync_suppressed_total 7033
telemt_desync_frames_bucket_total{bucket="1_2"} 2007
telemt_desync_frames_bucket_total{bucket="3_10"} 4272
telemt_desync_frames_bucket_total{bucket="gt_10"} 4571
telemt_pool_swap_total 67
telemt_pool_force_close_total 1717
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 21898
telemt_me_writer_removed_unexpected_total 437
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1512
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20850
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1653
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20181
telemt_me_writer_teardown_success_total{mode="normal"} 22362
telemt_me_writer_teardown_noop_total 21898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44260
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.709521
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44260
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 394
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2265004
telemt_user_connections_current{user="hello"} 3303
telemt_user_octets_from_client{user="hello"} 47724122532 (44.45 GB)
telemt_user_octets_to_client{user="hello"} 1049853444532 (977.75 GB)
telemt_user_unique_ips_current{user="hello"} 1402
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 60096.3 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082782
telemt_connections_bad_total 135128
telemt_connections_current 717
telemt_connections_me_current 717
telemt_handshake_timeouts_total 380297
telemt_upstream_connect_attempt_total 28176
telemt_upstream_connect_success_total 28173
telemt_upstream_connect_attempts_per_request{bucket="1"} 28173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1193
telemt_me_reconnect_success_total 463
telemt_me_reader_eof_total 461
telemt_me_idle_close_by_peer_total 461
telemt_me_route_drop_no_conn_total 225603
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497009
telemt_me_endpoint_quarantine_total 553
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 507
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 3256
telemt_desync_full_logged_total 1207
telemt_desync_suppressed_total 2049
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 1160
telemt_desync_frames_bucket_total{bucket="gt_10"} 1518
telemt_pool_swap_total 66
telemt_pool_force_close_total 1499
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 25257
telemt_me_writer_removed_unexpected_total 435
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1852
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23851
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23758
telemt_me_writer_teardown_success_total{mode="normal"} 25703
telemt_me_writer_teardown_noop_total 25257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50960
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.350811
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50960
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 496787
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 9249419263 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 188322900881 (175.39 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 62114.8 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3577234
telemt_connections_bad_total 331961
telemt_connections_current 4613
telemt_connections_me_current 4613
telemt_handshake_timeouts_total 109465
telemt_upstream_connect_attempt_total 25282
telemt_upstream_connect_success_total 25179
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 25251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1029
telemt_me_reconnect_success_total 581
telemt_me_reader_eof_total 541
telemt_me_idle_close_by_peer_total 541
telemt_me_route_drop_no_conn_total 1043675
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2832087
telemt_me_endpoint_quarantine_total 464
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 477
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 11317
telemt_desync_full_logged_total 3719
telemt_desync_suppressed_total 7598
telemt_desync_frames_bucket_total{bucket="1_2"} 2691
telemt_desync_frames_bucket_total{bucket="3_10"} 4204
telemt_desync_frames_bucket_total{bucket="gt_10"} 4422
telemt_pool_swap_total 68
telemt_pool_force_close_total 1759
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 189
telemt_me_draining_writers_reap_progress_total 22706
telemt_me_writer_removed_unexpected_total 531
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1772
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21464
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1727
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20947
telemt_me_writer_teardown_success_total{mode="normal"} 23236
telemt_me_writer_teardown_noop_total 22706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45942
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.650865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45942
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 189
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 513
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 2824591
telemt_user_connections_current{user="hello"} 4614
telemt_user_octets_from_client{user="hello"} 59731445368 (55.63 GB)
telemt_user_octets_to_client{user="hello"} 1333456939628 (1.21 TB)
telemt_user_unique_ips_current{user="hello"} 1664
telemt_user_unique_ips_recent_window{user="hello"} 650
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 62111.5 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3222858
telemt_connections_bad_total 281446
telemt_connections_current 3823
telemt_connections_me_current 3823
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 94309
telemt_upstream_connect_attempt_total 41447
telemt_upstream_connect_success_total 41180
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 41402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 588
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_reconnect_attempts_total 3532
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 654
telemt_me_idle_close_by_peer_total 654
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 1086612
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2587076
telemt_me_endpoint_quarantine_total 524
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 476
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 10006
telemt_desync_full_logged_total 3416
telemt_desync_suppressed_total 6590
telemt_desync_frames_bucket_total{bucket="1_2"} 2537
telemt_desync_frames_bucket_total{bucket="3_10"} 3700
telemt_desync_frames_bucket_total{bucket="gt_10"} 3769
telemt_pool_swap_total 67
telemt_pool_force_close_total 1706
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 21846
telemt_me_writer_removed_unexpected_total 666
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2073
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20469
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20140
telemt_me_writer_teardown_success_total{mode="normal"} 22542
telemt_me_writer_teardown_noop_total 21847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44389
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.186318
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44389
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 570
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2596305
telemt_user_connections_current{user="hello"} 3823
telemt_user_octets_from_client{user="hello"} 47349960861 (44.10 GB)
telemt_user_octets_to_client{user="hello"} 1128464884188 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1562
telemt_user_unique_ips_recent_window{user="hello"} 532
```