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

# Server Metrics 2026-03-21 22:00:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 3275.9 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65939
telemt_connections_bad_total 4730
telemt_connections_current 775
telemt_connections_me_current 775
telemt_handshake_timeouts_total 2958
telemt_upstream_connect_attempt_total 1347
telemt_upstream_connect_success_total 1346
telemt_upstream_connect_attempts_per_request{bucket="1"} 1346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 31
telemt_me_reconnect_success_total 11
telemt_me_reader_eof_total 13
telemt_me_idle_close_by_peer_total 13
telemt_me_route_drop_no_conn_total 14833
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53060
telemt_me_endpoint_quarantine_total 19
telemt_me_single_endpoint_shadow_rotate_total 30
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
telemt_me_writers_active_current 43
telemt_desync_total 387
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 264
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 3
telemt_pool_force_close_total 76
telemt_me_writer_close_signal_drop_total 8
telemt_me_draining_writers_reap_progress_total 1152
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1098
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1076
telemt_me_writer_teardown_success_total{mode="normal"} 1165
telemt_me_writer_teardown_noop_total 1152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.988996
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 8
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 53015
telemt_user_connections_current{user="hello"} 775
telemt_user_octets_from_client{user="hello"} 722266384 (688.81 MB)
telemt_user_octets_to_client{user="hello"} 17480998116 (16.28 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 16642.6 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578093
telemt_connections_bad_total 26997
telemt_connections_current 618
telemt_connections_me_current 618
telemt_handshake_timeouts_total 20582
telemt_upstream_connect_attempt_total 6728
telemt_upstream_connect_success_total 6597
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 6713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_reconnect_attempts_total 594
telemt_me_reconnect_success_total 213
telemt_me_reader_eof_total 180
telemt_me_idle_close_by_peer_total 180
telemt_me_route_drop_no_conn_total 305894
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 468644
telemt_me_endpoint_quarantine_total 137
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 135
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 2097
telemt_desync_full_logged_total 1192
telemt_desync_suppressed_total 905
telemt_desync_frames_bucket_total{bucket="1_2"} 436
telemt_desync_frames_bucket_total{bucket="3_10"} 796
telemt_desync_frames_bucket_total{bucket="gt_10"} 865
telemt_pool_swap_total 18
telemt_pool_force_close_total 528
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 5899
telemt_me_writer_removed_unexpected_total 169
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5551
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5371
telemt_me_writer_teardown_success_total{mode="normal"} 6066
telemt_me_writer_teardown_noop_total 5899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11965
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.916625
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11965
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 144
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 468012
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 8198683924 (7.64 GB)
telemt_user_octets_to_client{user="hello"} 155968316316 (145.26 GB)
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 91502.0 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7183400
telemt_connections_bad_total 554277
telemt_connections_current 2558
telemt_connections_me_current 2558
telemt_handshake_timeouts_total 224236
telemt_upstream_connect_attempt_total 32908
telemt_upstream_connect_success_total 32840
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 32847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1445
telemt_me_reconnect_success_total 697
telemt_me_reader_eof_total 709
telemt_me_idle_close_by_peer_total 709
telemt_me_route_drop_no_conn_total 4442991
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5875020
telemt_me_endpoint_quarantine_total 574
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 678
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 24789
telemt_desync_full_logged_total 8161
telemt_desync_suppressed_total 16628
telemt_desync_frames_bucket_total{bucket="1_2"} 5332
telemt_desync_frames_bucket_total{bucket="3_10"} 9718
telemt_desync_frames_bucket_total{bucket="gt_10"} 9739
telemt_pool_swap_total 98
telemt_pool_force_close_total 3315
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 545
telemt_me_draining_writers_reap_progress_total 29968
telemt_me_writer_removed_unexpected_total 681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2566
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27676
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3077
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26653
telemt_me_writer_teardown_success_total{mode="normal"} 30242
telemt_me_writer_teardown_noop_total 30012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60254
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 147.751459
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60254
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 545
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5867882
telemt_user_connections_current{user="hello"} 2558
telemt_user_octets_from_client{user="hello"} 100849950284 (93.92 GB)
telemt_user_octets_to_client{user="hello"} 1889860113344 (1.72 TB)
telemt_user_unique_ips_current{user="hello"} 1138
telemt_user_unique_ips_recent_window{user="hello"} 317
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 91503.4 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5880619
telemt_connections_bad_total 571507
telemt_connections_current 2331
telemt_connections_me_current 2331
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 191863
telemt_upstream_connect_attempt_total 36866
telemt_upstream_connect_success_total 36534
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 36706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17535
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1724
telemt_me_reconnect_success_total 729
telemt_me_reader_eof_total 704
telemt_me_idle_close_by_peer_total 704
telemt_me_route_drop_no_conn_total 2045603
telemt_me_route_drop_channel_closed_total 234
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4385586
telemt_me_endpoint_quarantine_total 556
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 699
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 21150
telemt_desync_full_logged_total 7052
telemt_desync_suppressed_total 14098
telemt_desync_frames_bucket_total{bucket="1_2"} 5118
telemt_desync_frames_bucket_total{bucket="3_10"} 8187
telemt_desync_frames_bucket_total{bucket="gt_10"} 7845
telemt_pool_swap_total 100
telemt_pool_force_close_total 3037
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 339
telemt_me_draining_writers_reap_progress_total 28575
telemt_me_writer_removed_unexpected_total 682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2468
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26720
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2838
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25538
telemt_me_writer_teardown_success_total{mode="normal"} 29188
telemt_me_writer_teardown_noop_total 28581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57769
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.425053
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57769
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 339
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 628
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4361205
telemt_user_connections_current{user="hello"} 2331
telemt_user_octets_from_client{user="hello"} 134137072313 (124.92 GB)
telemt_user_octets_to_client{user="hello"} 2024662550827 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1005
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 91467.4 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5804478
telemt_connections_bad_total 529368
telemt_connections_current 2146
telemt_connections_me_current 2146
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 180697
telemt_upstream_connect_attempt_total 43298
telemt_upstream_connect_success_total 43007
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 43142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1760
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 739
telemt_me_idle_close_by_peer_total 739
telemt_me_route_drop_no_conn_total 2057836
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4351592
telemt_me_endpoint_quarantine_total 610
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 683
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 20952
telemt_desync_full_logged_total 6867
telemt_desync_suppressed_total 14085
telemt_desync_frames_bucket_total{bucket="1_2"} 5197
telemt_desync_frames_bucket_total{bucket="3_10"} 7950
telemt_desync_frames_bucket_total{bucket="gt_10"} 7805
telemt_pool_swap_total 98
telemt_pool_force_close_total 2913
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 349
telemt_me_draining_writers_reap_progress_total 30011
telemt_me_writer_removed_unexpected_total 708
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2554
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28170
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2698
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27098
telemt_me_writer_teardown_success_total{mode="normal"} 30724
telemt_me_writer_teardown_noop_total 30021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60745
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.767692
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60745
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 349
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 687
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 4353335
telemt_user_connections_current{user="hello"} 2146
telemt_user_octets_from_client{user="hello"} 127707075215 (118.94 GB)
telemt_user_octets_to_client{user="hello"} 1987464198543 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 933
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 91506.7 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19563439
telemt_connections_bad_total 1346822
telemt_connections_current 2935
telemt_connections_me_current 2935
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 553582
telemt_upstream_connect_attempt_total 182949
telemt_upstream_connect_success_total 165640
telemt_upstream_connect_fail_total 15820
telemt_upstream_connect_attempts_per_request{bucket="1"} 181460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8854
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15820
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59724
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1285
telemt_me_route_drop_no_conn_total 39379416
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16022538
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 665
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 711
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 30515
telemt_desync_full_logged_total 9027
telemt_desync_suppressed_total 21488
telemt_desync_frames_bucket_total{bucket="1_2"} 6671
telemt_desync_frames_bucket_total{bucket="3_10"} 13535
telemt_desync_frames_bucket_total{bucket="gt_10"} 10309
telemt_pool_swap_total 93
telemt_pool_force_close_total 3150
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 28246
telemt_me_writer_removed_unexpected_total 1836
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3846
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25963
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2642
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 508
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25096
telemt_me_writer_teardown_success_total{mode="normal"} 29809
telemt_me_writer_teardown_noop_total 28272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58081
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 207.259511
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58081
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 3520
telemt_me_writer_restored_same_endpoint_total 1374
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 16147552
telemt_user_connections_current{user="hello"} 2935
telemt_user_octets_from_client{user="hello"} 166084334326 (154.68 GB)
telemt_user_octets_to_client{user="hello"} 1032287176770 (961.39 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1253
telemt_user_unique_ips_recent_window{user="hello"} 356
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 91474.2 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5641322
telemt_connections_bad_total 531315
telemt_connections_current 2387
telemt_connections_me_current 2387
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 116527
telemt_upstream_connect_attempt_total 50668
telemt_upstream_connect_success_total 50140
telemt_upstream_connect_fail_total 442
telemt_upstream_connect_attempts_per_request{bucket="1"} 50582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 442
telemt_me_reconnect_attempts_total 11325
telemt_me_reconnect_success_total 1321
telemt_me_reader_eof_total 1234
telemt_me_idle_close_by_peer_total 1234
telemt_me_route_drop_no_conn_total 2318488
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4388669
telemt_me_endpoint_quarantine_total 566
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 682
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
telemt_me_writers_active_current 46
telemt_desync_total 22055
telemt_desync_full_logged_total 7643
telemt_desync_suppressed_total 14412
telemt_desync_frames_bucket_total{bucket="1_2"} 4217
telemt_desync_frames_bucket_total{bucket="3_10"} 8561
telemt_desync_frames_bucket_total{bucket="gt_10"} 9277
telemt_pool_swap_total 93
telemt_pool_force_close_total 2729
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 354
telemt_me_draining_writers_reap_progress_total 30933
telemt_me_writer_removed_unexpected_total 1225
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3165
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29007
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2361
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28204
telemt_me_writer_teardown_success_total{mode="normal"} 32172
telemt_me_writer_teardown_noop_total 30934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63106
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.614070
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63106
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 354
telemt_me_refill_failed_total 601
telemt_me_writer_restored_same_endpoint_total 1106
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 1516
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 4382048
telemt_user_connections_current{user="hello"} 2387
telemt_user_octets_from_client{user="hello"} 116610498084 (108.60 GB)
telemt_user_octets_to_client{user="hello"} 1778825100546 (1.62 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1069
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 28310.1 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3434094
telemt_connections_bad_total 123211
telemt_connections_current 1805
telemt_connections_me_current 1805
telemt_handshake_timeouts_total 1450087
telemt_upstream_connect_attempt_total 9538
telemt_upstream_connect_success_total 9417
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 9532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 2340
telemt_me_reconnect_success_total 324
telemt_me_reader_eof_total 240
telemt_me_idle_close_by_peer_total 240
telemt_me_route_drop_no_conn_total 962862
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1645650
telemt_me_endpoint_quarantine_total 144
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 210
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 44
telemt_desync_total 9062
telemt_desync_full_logged_total 3041
telemt_desync_suppressed_total 6021
telemt_desync_frames_bucket_total{bucket="1_2"} 1628
telemt_desync_frames_bucket_total{bucket="3_10"} 3460
telemt_desync_frames_bucket_total{bucket="gt_10"} 3974
telemt_pool_swap_total 30
telemt_pool_force_close_total 971
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 91
telemt_me_draining_writers_reap_progress_total 8343
telemt_me_writer_removed_unexpected_total 262
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 761
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7854
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 852
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7372
telemt_me_writer_teardown_success_total{mode="normal"} 8615
telemt_me_writer_teardown_noop_total 8344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.558844
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 91
telemt_me_refill_failed_total 123
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 690
telemt_user_connections_total{user="hello"} 1640854
telemt_user_connections_current{user="hello"} 1805
telemt_user_octets_from_client{user="hello"} 47587019380 (44.32 GB)
telemt_user_octets_to_client{user="hello"} 705403991884 (656.96 GB)
telemt_user_unique_ips_current{user="hello"} 837
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 9280.9 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118024
telemt_connections_bad_total 1259
telemt_connections_current 496
telemt_connections_me_current 496
telemt_handshake_timeouts_total 3203
telemt_upstream_connect_attempt_total 3990
telemt_upstream_connect_success_total 3978
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 3989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 75
telemt_me_reconnect_success_total 43
telemt_me_reader_eof_total 43
telemt_me_idle_close_by_peer_total 43
telemt_me_route_drop_no_conn_total 33074
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101550
telemt_me_endpoint_quarantine_total 71
telemt_me_single_endpoint_shadow_rotate_total 85
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
telemt_me_writers_active_current 44
telemt_desync_total 873
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 665
telemt_desync_frames_bucket_total{bucket="1_2"} 372
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 10
telemt_pool_force_close_total 262
telemt_me_writer_close_signal_drop_total 12
telemt_me_draining_writers_reap_progress_total 3516
telemt_me_writer_removed_unexpected_total 43
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 226
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3333
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 260
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3254
telemt_me_writer_teardown_success_total{mode="normal"} 3559
telemt_me_writer_teardown_noop_total 3516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7075
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.527154
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7075
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 12
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 101407
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 2161256692 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 63603580108 (59.24 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 91478.6 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6718043
telemt_connections_bad_total 678294
telemt_connections_current 2660
telemt_connections_me_current 2660
telemt_handshake_timeouts_total 193745
telemt_upstream_connect_attempt_total 34592
telemt_upstream_connect_success_total 34454
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 34555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 1419
telemt_me_reconnect_success_total 723
telemt_me_reader_eof_total 699
telemt_me_idle_close_by_peer_total 699
telemt_me_route_drop_no_conn_total 2053017
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5138695
telemt_me_endpoint_quarantine_total 609
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 697
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 44
telemt_desync_total 19679
telemt_desync_full_logged_total 6565
telemt_desync_suppressed_total 13114
telemt_desync_frames_bucket_total{bucket="1_2"} 4790
telemt_desync_frames_bucket_total{bucket="3_10"} 7183
telemt_desync_frames_bucket_total{bucket="gt_10"} 7706
telemt_pool_swap_total 101
telemt_pool_force_close_total 2764
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 31082
telemt_me_writer_removed_unexpected_total 680
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2515
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29256
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28318
telemt_me_writer_teardown_success_total{mode="normal"} 31771
telemt_me_writer_teardown_noop_total 31084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62855
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.145783
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62855
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 647
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 5114215
telemt_user_connections_current{user="hello"} 2660
telemt_user_octets_from_client{user="hello"} 103454812012 (96.35 GB)
telemt_user_octets_to_client{user="hello"} 2398707929552 (2.18 TB)
telemt_user_unique_ips_current{user="hello"} 1084
telemt_user_unique_ips_recent_window{user="hello"} 326
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 91475.3 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5725384
telemt_connections_bad_total 543550
telemt_connections_current 2291
telemt_connections_me_current 2291
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 162190
telemt_upstream_connect_attempt_total 50803
telemt_upstream_connect_success_total 50421
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 50744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19144
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_reconnect_attempts_total 5208
telemt_me_reconnect_success_total 1033
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2106411
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4503547
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 695
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
telemt_me_writers_active_current 51
telemt_desync_total 18304
telemt_desync_full_logged_total 6185
telemt_desync_suppressed_total 12119
telemt_desync_frames_bucket_total{bucket="1_2"} 4541
telemt_desync_frames_bucket_total{bucket="3_10"} 6690
telemt_desync_frames_bucket_total{bucket="gt_10"} 7073
telemt_pool_swap_total 99
telemt_pool_force_close_total 2713
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 352
telemt_me_draining_writers_reap_progress_total 30099
telemt_me_writer_removed_unexpected_total 919
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28039
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2500
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27386
telemt_me_writer_teardown_success_total{mode="normal"} 31060
telemt_me_writer_teardown_noop_total 30103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61163
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.216653
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61163
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 352
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 796
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 4507200
telemt_user_connections_current{user="hello"} 2291
telemt_user_octets_from_client{user="hello"} 86285884333 (80.36 GB)
telemt_user_octets_to_client{user="hello"} 1924211660780 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1003
telemt_user_unique_ips_recent_window{user="hello"} 280
```