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

# Server Metrics 2026-03-22 03:11:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 21912.6 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325443
telemt_connections_bad_total 21867
telemt_connections_current 804
telemt_connections_me_current 804
telemt_handshake_timeouts_total 18608
telemt_upstream_connect_attempt_total 9224
telemt_upstream_connect_success_total 9223
telemt_upstream_connect_attempts_per_request{bucket="1"} 9223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5900
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 274
telemt_me_reconnect_success_total 148
telemt_me_reader_eof_total 144
telemt_me_idle_close_by_peer_total 144
telemt_me_route_drop_no_conn_total 61755
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267907
telemt_me_endpoint_quarantine_total 178
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 45
telemt_desync_total 2356
telemt_desync_full_logged_total 642
telemt_desync_suppressed_total 1714
telemt_desync_frames_bucket_total{bucket="1_2"} 791
telemt_desync_frames_bucket_total{bucket="3_10"} 881
telemt_desync_frames_bucket_total{bucket="gt_10"} 684
telemt_pool_swap_total 24
telemt_pool_force_close_total 629
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 8301
telemt_me_writer_removed_unexpected_total 143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 567
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7868
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 624
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7672
telemt_me_writer_teardown_success_total{mode="normal"} 8435
telemt_me_writer_teardown_noop_total 8302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16737
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.966357
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16737
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 134
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 267384
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 3182706360 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 95935482580 (89.35 GB)
telemt_user_unique_ips_current{user="hello"} 382
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 35277.5 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812906
telemt_connections_bad_total 52016
telemt_connections_current 862
telemt_connections_me_current 862
telemt_handshake_timeouts_total 29915
telemt_upstream_connect_attempt_total 16467
telemt_upstream_connect_success_total 16209
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 16444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_reconnect_attempts_total 1372
telemt_me_reconnect_success_total 509
telemt_me_reader_eof_total 449
telemt_me_idle_close_by_peer_total 449
telemt_me_route_drop_no_conn_total 344659
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642179
telemt_me_endpoint_quarantine_total 336
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 286
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 2782
telemt_desync_full_logged_total 1596
telemt_desync_suppressed_total 1186
telemt_desync_frames_bucket_total{bucket="1_2"} 589
telemt_desync_frames_bucket_total{bucket="3_10"} 1064
telemt_desync_frames_bucket_total{bucket="gt_10"} 1129
telemt_pool_swap_total 38
telemt_pool_force_close_total 1004
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 14592
telemt_me_writer_removed_unexpected_total 426
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1221
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13807
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13588
telemt_me_writer_teardown_success_total{mode="normal"} 15028
telemt_me_writer_teardown_noop_total 14592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.768343
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 641257
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 10493512824 (9.77 GB)
telemt_user_octets_to_client{user="hello"} 228024245492 (212.36 GB)
telemt_user_unique_ips_current{user="hello"} 593
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 110137.6 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7805221
telemt_connections_bad_total 638324
telemt_connections_current 1570
telemt_connections_me_current 1570
telemt_handshake_timeouts_total 256332
telemt_upstream_connect_attempt_total 40990
telemt_upstream_connect_success_total 40915
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 40922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22226
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1595
telemt_me_reconnect_success_total 833
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 4545070
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6311448
telemt_me_endpoint_quarantine_total 711
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 823
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
telemt_desync_total 26557
telemt_desync_full_logged_total 8798
telemt_desync_suppressed_total 17759
telemt_desync_frames_bucket_total{bucket="1_2"} 5733
telemt_desync_frames_bucket_total{bucket="3_10"} 10367
telemt_desync_frames_bucket_total{bucket="gt_10"} 10457
telemt_pool_swap_total 119
telemt_pool_force_close_total 3936
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 37395
telemt_me_writer_removed_unexpected_total 810
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3133
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34607
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3697
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33459
telemt_me_writer_teardown_success_total{mode="normal"} 37740
telemt_me_writer_teardown_noop_total 37439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 160.791891
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6303510
telemt_user_connections_current{user="hello"} 1570
telemt_user_octets_from_client{user="hello"} 107363153380 (99.99 GB)
telemt_user_octets_to_client{user="hello"} 2102520491708 (1.91 TB)
telemt_user_unique_ips_current{user="hello"} 759
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 110138.8 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6451924
telemt_connections_bad_total 589506
telemt_connections_current 1747
telemt_connections_me_current 1747
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 214026
telemt_upstream_connect_attempt_total 45009
telemt_upstream_connect_success_total 44618
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 44812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1952
telemt_me_reconnect_success_total 883
telemt_me_reader_eof_total 854
telemt_me_idle_close_by_peer_total 854
telemt_me_route_drop_no_conn_total 2265647
telemt_me_route_drop_channel_closed_total 264
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4815918
telemt_me_endpoint_quarantine_total 693
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 849
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
telemt_me_writers_active_current 43
telemt_desync_total 22714
telemt_desync_full_logged_total 7742
telemt_desync_suppressed_total 14972
telemt_desync_frames_bucket_total{bucket="1_2"} 5467
telemt_desync_frames_bucket_total{bucket="3_10"} 8823
telemt_desync_frames_bucket_total{bucket="gt_10"} 8424
telemt_pool_swap_total 120
telemt_pool_force_close_total 3571
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 35938
telemt_me_writer_removed_unexpected_total 839
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2987
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33727
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32367
telemt_me_writer_teardown_success_total{mode="normal"} 36714
telemt_me_writer_teardown_noop_total 35944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72658
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.451765
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72658
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4738010
telemt_user_connections_current{user="hello"} 1747
telemt_user_octets_from_client{user="hello"} 140800926353 (131.13 GB)
telemt_user_octets_to_client{user="hello"} 2241692793335 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 808
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 110103.9 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6328496
telemt_connections_bad_total 549382
telemt_connections_current 1432
telemt_connections_me_current 1432
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 205051
telemt_upstream_connect_attempt_total 51095
telemt_upstream_connect_success_total 50717
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 50853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1079
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2080
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 2159285
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4702102
telemt_me_endpoint_quarantine_total 777
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 823
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 22647
telemt_desync_full_logged_total 7625
telemt_desync_suppressed_total 15022
telemt_desync_frames_bucket_total{bucket="1_2"} 5530
telemt_desync_frames_bucket_total{bucket="3_10"} 8674
telemt_desync_frames_bucket_total{bucket="gt_10"} 8443
telemt_pool_swap_total 119
telemt_pool_force_close_total 3454
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 37014
telemt_me_writer_removed_unexpected_total 839
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3070
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34800
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33560
telemt_me_writer_teardown_success_total{mode="normal"} 37870
telemt_me_writer_teardown_noop_total 37026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74896
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.833553
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74896
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 800
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 4697595
telemt_user_connections_current{user="hello"} 1432
telemt_user_octets_from_client{user="hello"} 134285611063 (125.06 GB)
telemt_user_octets_to_client{user="hello"} 2153892664683 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 690
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 110142.1 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20503202
telemt_connections_bad_total 1649163
telemt_connections_current 2429
telemt_connections_me_current 2429
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 613499
telemt_upstream_connect_attempt_total 199963
telemt_upstream_connect_success_total 181850
telemt_upstream_connect_fail_total 16344
telemt_upstream_connect_attempts_per_request{bucket="1"} 198194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8931
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16344
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65029
telemt_me_reconnect_success_total 2343
telemt_me_reader_eof_total 1473
telemt_me_idle_close_by_peer_total 1472
telemt_me_route_drop_no_conn_total 39523607
telemt_me_route_drop_channel_closed_total 125
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16552261
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 864
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 862
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 64
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
telemt_desync_total 32060
telemt_desync_full_logged_total 9636
telemt_desync_suppressed_total 22424
telemt_desync_frames_bucket_total{bucket="1_2"} 6944
telemt_desync_frames_bucket_total{bucket="3_10"} 14230
telemt_desync_frames_bucket_total{bucket="gt_10"} 10886
telemt_pool_swap_total 114
telemt_pool_force_close_total 3686
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 806
telemt_me_draining_writers_reap_progress_total 34597
telemt_me_writer_removed_unexpected_total 2171
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4659
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31850
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3161
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 525
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30911
telemt_me_writer_teardown_success_total{mode="normal"} 36509
telemt_me_writer_teardown_noop_total 34624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71133
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.247028
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71133
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 806
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 546
telemt_user_connections_total{user="hello"} 16685359
telemt_user_connections_current{user="hello"} 2429
telemt_user_octets_from_client{user="hello"} 224605018176 (209.18 GB)
telemt_user_octets_to_client{user="hello"} 1219985628905 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 1121
telemt_user_unique_ips_recent_window{user="hello"} 292
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 110109.7 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6076708
telemt_connections_bad_total 577099
telemt_connections_current 1309
telemt_connections_me_current 1309
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 127574
telemt_upstream_connect_attempt_total 59796
telemt_upstream_connect_success_total 59104
telemt_upstream_connect_fail_total 591
telemt_upstream_connect_attempts_per_request{bucket="1"} 59695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 591
telemt_me_reconnect_attempts_total 69725
telemt_me_reconnect_success_total 1808
telemt_me_reader_eof_total 1591
telemt_me_idle_close_by_peer_total 1590
telemt_me_route_drop_no_conn_total 2396364
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4732559
telemt_me_endpoint_quarantine_total 748
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 837
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_active_current 42
telemt_desync_total 23534
telemt_desync_full_logged_total 8289
telemt_desync_suppressed_total 15245
telemt_desync_frames_bucket_total{bucket="1_2"} 4510
telemt_desync_frames_bucket_total{bucket="3_10"} 9113
telemt_desync_frames_bucket_total{bucket="gt_10"} 9911
telemt_pool_swap_total 114
telemt_pool_force_close_total 3268
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 38908
telemt_me_writer_removed_unexpected_total 1628
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36578
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35640
telemt_me_writer_teardown_success_total{mode="normal"} 40568
telemt_me_writer_teardown_noop_total 38909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.135039
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 4209
telemt_me_writer_restored_same_endpoint_total 1517
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 4725288
telemt_user_connections_current{user="hello"} 1309
telemt_user_octets_from_client{user="hello"} 125146641896 (116.55 GB)
telemt_user_octets_to_client{user="hello"} 1927054817506 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 638
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 46945.4 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3994038
telemt_connections_bad_total 151861
telemt_connections_current 1708
telemt_connections_me_current 1708
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1623190
telemt_upstream_connect_attempt_total 28450
telemt_upstream_connect_success_total 28268
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 28443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_reconnect_attempts_total 45834
telemt_me_reconnect_success_total 979
telemt_me_reader_eof_total 663
telemt_me_idle_close_by_peer_total 663
telemt_me_route_drop_no_conn_total 1028249
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1956126
telemt_me_endpoint_quarantine_total 355
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 361
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10572
telemt_desync_full_logged_total 3653
telemt_desync_suppressed_total 6919
telemt_desync_frames_bucket_total{bucket="1_2"} 1910
telemt_desync_frames_bucket_total{bucket="3_10"} 4055
telemt_desync_frames_bucket_total{bucket="gt_10"} 4607
telemt_pool_swap_total 51
telemt_pool_force_close_total 1509
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 17388
telemt_me_writer_removed_unexpected_total 736
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1565
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15879
telemt_me_writer_teardown_success_total{mode="normal"} 18151
telemt_me_writer_teardown_noop_total 17390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35541
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.491352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35541
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 877
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1959699
telemt_user_connections_current{user="hello"} 1708
telemt_user_octets_from_client{user="hello"} 54632304500 (50.88 GB)
telemt_user_octets_to_client{user="hello"} 830680032250 (773.63 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 896
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 27919.2 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203963
telemt_connections_bad_total 1752
telemt_connections_current 396
telemt_connections_me_current 396
telemt_handshake_timeouts_total 5580
telemt_upstream_connect_attempt_total 13419
telemt_upstream_connect_success_total 13387
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 294
telemt_me_reconnect_success_total 171
telemt_me_reader_eof_total 176
telemt_me_idle_close_by_peer_total 176
telemt_me_route_drop_no_conn_total 56424
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180006
telemt_me_endpoint_quarantine_total 271
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1046
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 781
telemt_desync_frames_bucket_total{bucket="1_2"} 393
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 30
telemt_pool_force_close_total 669
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 12127
telemt_me_writer_removed_unexpected_total 169
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 765
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11538
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 667
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11458
telemt_me_writer_teardown_success_total{mode="normal"} 12303
telemt_me_writer_teardown_noop_total 12127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24430
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.040258
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24430
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 155
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 179688
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 3210117504 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 112501161100 (104.77 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 110114.4 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7397897
telemt_connections_bad_total 744631
telemt_connections_current 1697
telemt_connections_me_current 1697
telemt_handshake_timeouts_total 210382
telemt_upstream_connect_attempt_total 43268
telemt_upstream_connect_success_total 43109
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 43231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 1592
telemt_me_reconnect_success_total 857
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 2134530
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5518777
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 848
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 21669
telemt_desync_full_logged_total 7098
telemt_desync_suppressed_total 14571
telemt_desync_frames_bucket_total{bucket="1_2"} 5450
telemt_desync_frames_bucket_total{bucket="3_10"} 7841
telemt_desync_frames_bucket_total{bucket="gt_10"} 8378
telemt_pool_swap_total 122
telemt_pool_force_close_total 3260
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 392
telemt_me_draining_writers_reap_progress_total 39038
telemt_me_writer_removed_unexpected_total 811
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3060
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36810
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3172
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35778
telemt_me_writer_teardown_success_total{mode="normal"} 39870
telemt_me_writer_teardown_noop_total 39040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.678722
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 392
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 766
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 5493756
telemt_user_connections_current{user="hello"} 1697
telemt_user_octets_from_client{user="hello"} 110068633436 (102.51 GB)
telemt_user_octets_to_client{user="hello"} 2560982994756 (2.33 TB)
telemt_user_unique_ips_current{user="hello"} 793
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 110110.9 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6389261
telemt_connections_bad_total 631218
telemt_connections_current 1685
telemt_connections_me_current 1685
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 174143
telemt_upstream_connect_attempt_total 59057
telemt_upstream_connect_success_total 58612
telemt_upstream_connect_fail_total 386
telemt_upstream_connect_attempts_per_request{bucket="1"} 58998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23376
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 386
telemt_me_reconnect_attempts_total 5593
telemt_me_reconnect_success_total 1192
telemt_me_reader_eof_total 1077
telemt_me_idle_close_by_peer_total 1077
telemt_me_seq_mismatch_total 49
telemt_me_route_drop_no_conn_total 2188047
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4886943
telemt_me_endpoint_quarantine_total 873
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 843
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
telemt_desync_total 20252
telemt_desync_full_logged_total 6749
telemt_desync_suppressed_total 13503
telemt_desync_frames_bucket_total{bucket="1_2"} 5183
telemt_desync_frames_bucket_total{bucket="3_10"} 7385
telemt_desync_frames_bucket_total{bucket="gt_10"} 7684
telemt_pool_swap_total 120
telemt_pool_force_close_total 3219
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 37579
telemt_me_writer_removed_unexpected_total 1088
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3590
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35130
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2996
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34360
telemt_me_writer_teardown_success_total{mode="normal"} 38720
telemt_me_writer_teardown_noop_total 37583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76303
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.099009
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76303
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 932
telemt_me_writer_restored_fallback_total 66
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4889891
telemt_user_connections_current{user="hello"} 1685
telemt_user_octets_from_client{user="hello"} 92442596233 (86.09 GB)
telemt_user_octets_to_client{user="hello"} 2089741855908 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 735
telemt_user_unique_ips_recent_window{user="hello"} 192
```