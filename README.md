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

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
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
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
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

# Server Metrics 2026-03-22 02:05:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 17924.8 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257866
telemt_connections_bad_total 18298
telemt_connections_current 831
telemt_connections_me_current 831
telemt_handshake_timeouts_total 14884
telemt_upstream_connect_attempt_total 7455
telemt_upstream_connect_success_total 7454
telemt_upstream_connect_attempts_per_request{bucket="1"} 7454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4730
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 247
telemt_me_reconnect_success_total 121
telemt_me_reader_eof_total 119
telemt_me_idle_close_by_peer_total 119
telemt_me_route_drop_no_conn_total 47386
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210725
telemt_me_endpoint_quarantine_total 144
telemt_me_single_endpoint_shadow_rotate_total 150
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 1876
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1362
telemt_desync_frames_bucket_total{bucket="1_2"} 593
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 19
telemt_pool_force_close_total 494
telemt_me_writer_close_signal_drop_total 33
telemt_me_draining_writers_reap_progress_total 6694
telemt_me_writer_removed_unexpected_total 119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 469
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6334
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6200
telemt_me_writer_teardown_success_total{mode="normal"} 6803
telemt_me_writer_teardown_noop_total 6695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13498
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.239891
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13498
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 33
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 110
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 210358
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 2259438712 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 73665340216 (68.61 GB)
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 31291.4 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759416
telemt_connections_bad_total 43762
telemt_connections_current 662
telemt_connections_me_current 662
telemt_handshake_timeouts_total 28171
telemt_upstream_connect_attempt_total 14410
telemt_upstream_connect_success_total 14179
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 14389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_reconnect_attempts_total 1223
telemt_me_reconnect_success_total 455
telemt_me_reader_eof_total 398
telemt_me_idle_close_by_peer_total 398
telemt_me_route_drop_no_conn_total 337465
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606339
telemt_me_endpoint_quarantine_total 298
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 17
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 17
telemt_me_single_endpoint_shadow_rotate_total 253
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_me_writers_active_current 47
telemt_desync_total 2648
telemt_desync_full_logged_total 1514
telemt_desync_suppressed_total 1134
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 1005
telemt_desync_frames_bucket_total{bucket="gt_10"} 1082
telemt_pool_swap_total 33
telemt_pool_force_close_total 909
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 12767
telemt_me_writer_removed_unexpected_total 379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1080
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12072
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 887
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11858
telemt_me_writer_teardown_success_total{mode="normal"} 13152
telemt_me_writer_teardown_noop_total 12767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25919
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.536531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25919
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 334
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 605448
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 9982569360 (9.30 GB)
telemt_user_octets_to_client{user="hello"} 216579456960 (201.71 GB)
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 106151.8 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7673487
telemt_connections_bad_total 621976
telemt_connections_current 1872
telemt_connections_me_current 1872
telemt_handshake_timeouts_total 251869
telemt_upstream_connect_attempt_total 39157
telemt_upstream_connect_success_total 39084
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 39091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1558
telemt_me_reconnect_success_total 798
telemt_me_reader_eof_total 807
telemt_me_idle_close_by_peer_total 807
telemt_me_route_drop_no_conn_total 4527424
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6220509
telemt_me_endpoint_quarantine_total 681
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 792
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26303
telemt_desync_full_logged_total 8696
telemt_desync_suppressed_total 17607
telemt_desync_frames_bucket_total{bucket="1_2"} 5669
telemt_desync_frames_bucket_total{bucket="3_10"} 10264
telemt_desync_frames_bucket_total{bucket="gt_10"} 10370
telemt_pool_swap_total 114
telemt_pool_force_close_total 3810
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 598
telemt_me_draining_writers_reap_progress_total 35721
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2984
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33057
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3571
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31911
telemt_me_writer_teardown_success_total{mode="normal"} 36041
telemt_me_writer_teardown_noop_total 35765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71806
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 157.445469
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71806
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 598
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 709
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 6212712
telemt_user_connections_current{user="hello"} 1872
telemt_user_octets_from_client{user="hello"} 105883464920 (98.61 GB)
telemt_user_octets_to_client{user="hello"} 2062509106660 (1.88 TB)
telemt_user_unique_ips_current{user="hello"} 954
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 106153.0 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6327552
telemt_connections_bad_total 585100
telemt_connections_current 1514
telemt_connections_me_current 1514
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 209542
telemt_upstream_connect_attempt_total 43177
telemt_upstream_connect_success_total 42791
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 42980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1918
telemt_me_reconnect_success_total 865
telemt_me_reader_eof_total 835
telemt_me_idle_close_by_peer_total 835
telemt_me_route_drop_no_conn_total 2249249
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4737185
telemt_me_endpoint_quarantine_total 658
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 814
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22477
telemt_desync_full_logged_total 7636
telemt_desync_suppressed_total 14841
telemt_desync_frames_bucket_total{bucket="1_2"} 5415
telemt_desync_frames_bucket_total{bucket="3_10"} 8720
telemt_desync_frames_bucket_total{bucket="gt_10"} 8342
telemt_pool_swap_total 115
telemt_pool_force_close_total 3444
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 34239
telemt_me_writer_removed_unexpected_total 820
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2891
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32105
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3231
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30795
telemt_me_writer_teardown_success_total{mode="normal"} 34996
telemt_me_writer_teardown_noop_total 34245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69241
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.257548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69241
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 756
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 4659429
telemt_user_connections_current{user="hello"} 1514
telemt_user_octets_from_client{user="hello"} 139812638869 (130.21 GB)
telemt_user_octets_to_client{user="hello"} 2194070842199 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 750
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 106116.7 (29h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6213250
telemt_connections_bad_total 546043
telemt_connections_current 1487
telemt_connections_me_current 1487
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 200528
telemt_upstream_connect_attempt_total 49450
telemt_upstream_connect_success_total 49094
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 49230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1960
telemt_me_reconnect_success_total 886
telemt_me_reader_eof_total 829
telemt_me_idle_close_by_peer_total 829
telemt_me_route_drop_no_conn_total 2142119
telemt_me_route_drop_channel_closed_total 119
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4630304
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 793
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 22311
telemt_desync_full_logged_total 7491
telemt_desync_suppressed_total 14820
telemt_desync_frames_bucket_total{bucket="1_2"} 5451
telemt_desync_frames_bucket_total{bucket="3_10"} 8549
telemt_desync_frames_bucket_total{bucket="gt_10"} 8311
telemt_pool_swap_total 114
telemt_pool_force_close_total 3314
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 35557
telemt_me_writer_removed_unexpected_total 802
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2939
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33433
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3099
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32243
telemt_me_writer_teardown_success_total{mode="normal"} 36372
telemt_me_writer_teardown_noop_total 35568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.758026
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 769
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4625981
telemt_user_connections_current{user="hello"} 1487
telemt_user_octets_from_client{user="hello"} 133225931243 (124.08 GB)
telemt_user_octets_to_client{user="hello"} 2113035141759 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 717
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 106155.8 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20310534
telemt_connections_bad_total 1587944
telemt_connections_current 2087
telemt_connections_me_current 2087
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 598861
telemt_upstream_connect_attempt_total 194505
telemt_upstream_connect_success_total 176562
telemt_upstream_connect_fail_total 16222
telemt_upstream_connect_attempts_per_request{bucket="1"} 192784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8912
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16222
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64823
telemt_me_reconnect_success_total 2289
telemt_me_reader_eof_total 1428
telemt_me_idle_close_by_peer_total 1427
telemt_me_route_drop_no_conn_total 39494814
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16444349
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 828
telemt_me_single_endpoint_outage_enter_total 133
telemt_me_single_endpoint_outage_exit_total 133
telemt_me_single_endpoint_outage_reconnect_attempt_total 283
telemt_me_single_endpoint_outage_reconnect_success_total 68
telemt_me_single_endpoint_quarantine_bypass_total 283
telemt_me_single_endpoint_shadow_rotate_total 830
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_desync_total 31858
telemt_desync_full_logged_total 9532
telemt_desync_suppressed_total 22326
telemt_desync_frames_bucket_total{bucket="1_2"} 6901
telemt_desync_frames_bucket_total{bucket="3_10"} 14139
telemt_desync_frames_bucket_total{bucket="gt_10"} 10818
telemt_pool_swap_total 109
telemt_pool_force_close_total 3574
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 790
telemt_me_draining_writers_reap_progress_total 33128
telemt_me_writer_removed_unexpected_total 2129
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4483
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30512
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3051
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29554
telemt_me_writer_teardown_success_total{mode="normal"} 34995
telemt_me_writer_teardown_noop_total 33154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68149
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.627587
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68149
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 790
telemt_me_refill_failed_total 3801
telemt_me_writer_restored_same_endpoint_total 1570
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 16573896
telemt_user_connections_current{user="hello"} 2087
telemt_user_octets_from_client{user="hello"} 211447359702 (196.93 GB)
telemt_user_octets_to_client{user="hello"} 1180010007487 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 998
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 106123.1 (29h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5972584
telemt_connections_bad_total 559000
telemt_connections_current 1534
telemt_connections_me_current 1534
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 124823
telemt_upstream_connect_attempt_total 57915
telemt_upstream_connect_success_total 57240
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 57818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_reconnect_attempts_total 69634
telemt_me_reconnect_success_total 1773
telemt_me_reader_eof_total 1551
telemt_me_idle_close_by_peer_total 1550
telemt_me_route_drop_no_conn_total 2381890
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4661754
telemt_me_endpoint_quarantine_total 714
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 801
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 23273
telemt_desync_full_logged_total 8188
telemt_desync_suppressed_total 15085
telemt_desync_frames_bucket_total{bucket="1_2"} 4425
telemt_desync_frames_bucket_total{bucket="3_10"} 9007
telemt_desync_frames_bucket_total{bucket="gt_10"} 9841
telemt_pool_swap_total 109
telemt_pool_force_close_total 3157
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 37200
telemt_me_writer_removed_unexpected_total 1590
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3852
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34968
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2756
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34043
telemt_me_writer_teardown_success_total{mode="normal"} 38820
telemt_me_writer_teardown_noop_total 37201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76021
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.105119
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76021
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1485
telemt_me_writer_restored_fallback_total 33
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4654671
telemt_user_connections_current{user="hello"} 1534
telemt_user_octets_from_client{user="hello"} 123807247224 (115.30 GB)
telemt_user_octets_to_client{user="hello"} 1900795887510 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 765
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 42959.0 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3861159
telemt_connections_bad_total 140044
telemt_connections_current 1152
telemt_connections_me_current 1152
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1578906
telemt_upstream_connect_attempt_total 26353
telemt_upstream_connect_success_total 26182
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 26346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_reconnect_attempts_total 45798
telemt_me_reconnect_success_total 946
telemt_me_reader_eof_total 625
telemt_me_idle_close_by_peer_total 625
telemt_me_route_drop_no_conn_total 1015557
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1891317
telemt_me_endpoint_quarantine_total 320
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 329
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10351
telemt_desync_full_logged_total 3568
telemt_desync_suppressed_total 6783
telemt_desync_frames_bucket_total{bucket="1_2"} 1840
telemt_desync_frames_bucket_total{bucket="3_10"} 3973
telemt_desync_frames_bucket_total{bucket="gt_10"} 4538
telemt_pool_swap_total 46
telemt_pool_force_close_total 1429
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 15506
telemt_me_writer_removed_unexpected_total 702
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1469
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14762
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1223
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14077
telemt_me_writer_teardown_success_total{mode="normal"} 16231
telemt_me_writer_teardown_noop_total 15508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.345846
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 847
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1894980
telemt_user_connections_current{user="hello"} 1152
telemt_user_octets_from_client{user="hello"} 53642259948 (49.96 GB)
telemt_user_octets_to_client{user="hello"} 808549679138 (753.02 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 637
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 23930.1 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188064
telemt_connections_bad_total 1625
telemt_connections_current 366
telemt_connections_me_current 366
telemt_handshake_timeouts_total 5206
telemt_upstream_connect_attempt_total 11449
telemt_upstream_connect_success_total 11421
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 235
telemt_me_reconnect_success_total 149
telemt_me_reader_eof_total 151
telemt_me_idle_close_by_peer_total 151
telemt_me_route_drop_no_conn_total 51187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165649
telemt_me_endpoint_quarantine_total 239
telemt_me_single_endpoint_shadow_rotate_total 210
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 1008
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 754
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 26
telemt_pool_force_close_total 582
telemt_me_writer_close_signal_drop_total 22
telemt_me_draining_writers_reap_progress_total 10311
telemt_me_writer_removed_unexpected_total 146
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 675
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9787
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 580
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9729
telemt_me_writer_teardown_success_total{mode="normal"} 10462
telemt_me_writer_teardown_noop_total 10311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20773
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.955868
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20773
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 22
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 136
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 165340
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 3031871108 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 98847907504 (92.06 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 106127.6 (29h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7260144
telemt_connections_bad_total 738222
telemt_connections_current 1700
telemt_connections_me_current 1700
telemt_handshake_timeouts_total 206595
telemt_upstream_connect_attempt_total 41430
telemt_upstream_connect_success_total 41276
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 41393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_reconnect_attempts_total 1558
telemt_me_reconnect_success_total 840
telemt_me_reader_eof_total 822
telemt_me_idle_close_by_peer_total 822
telemt_me_route_drop_no_conn_total 2119234
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5440805
telemt_me_endpoint_quarantine_total 733
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 815
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_me_writers_active_current 47
telemt_desync_total 21391
telemt_desync_full_logged_total 7014
telemt_desync_suppressed_total 14377
telemt_desync_frames_bucket_total{bucket="1_2"} 5380
telemt_desync_frames_bucket_total{bucket="3_10"} 7742
telemt_desync_frames_bucket_total{bucket="gt_10"} 8269
telemt_pool_swap_total 117
telemt_pool_force_close_total 3149
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 37331
telemt_me_writer_removed_unexpected_total 793
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2950
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35193
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34182
telemt_me_writer_teardown_success_total{mode="normal"} 38143
telemt_me_writer_teardown_noop_total 37333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75476
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.621418
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75476
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 750
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5415835
telemt_user_connections_current{user="hello"} 1700
telemt_user_octets_from_client{user="hello"} 108999544220 (101.51 GB)
telemt_user_octets_to_client{user="hello"} 2525850686860 (2.30 TB)
telemt_user_unique_ips_current{user="hello"} 788
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 106124.0 (29h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6258423
telemt_connections_bad_total 618296
telemt_connections_current 1412
telemt_connections_me_current 1412
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 171921
telemt_upstream_connect_attempt_total 57191
telemt_upstream_connect_success_total 56765
telemt_upstream_connect_fail_total 367
telemt_upstream_connect_attempts_per_request{bucket="1"} 57132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 367
telemt_me_reconnect_attempts_total 5547
telemt_me_reconnect_success_total 1149
telemt_me_reader_eof_total 1031
telemt_me_idle_close_by_peer_total 1031
telemt_me_seq_mismatch_total 47
telemt_me_route_drop_no_conn_total 2172606
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4807866
telemt_me_endpoint_quarantine_total 843
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 811
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 20007
telemt_desync_full_logged_total 6651
telemt_desync_suppressed_total 13356
telemt_desync_frames_bucket_total{bucket="1_2"} 5106
telemt_desync_frames_bucket_total{bucket="3_10"} 7288
telemt_desync_frames_bucket_total{bucket="gt_10"} 7613
telemt_pool_swap_total 115
telemt_pool_force_close_total 3105
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 35886
telemt_me_writer_removed_unexpected_total 1045
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3461
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33518
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32781
telemt_me_writer_teardown_success_total{mode="normal"} 36979
telemt_me_writer_teardown_noop_total 35890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72869
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.999847
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72869
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 895
telemt_me_writer_restored_fallback_total 60
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4810969
telemt_user_connections_current{user="hello"} 1412
telemt_user_octets_from_client{user="hello"} 90388998029 (84.18 GB)
telemt_user_octets_to_client{user="hello"} 2056340172536 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 693
telemt_user_unique_ips_recent_window{user="hello"} 132
```