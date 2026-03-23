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

# Server Metrics 2026-03-23 02:22:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 105347.4 (29h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3616471
telemt_connections_bad_total 336972
telemt_connections_current 869
telemt_connections_me_current 869
telemt_handshake_timeouts_total 114606
telemt_upstream_connect_attempt_total 39253
telemt_upstream_connect_success_total 39252
telemt_upstream_connect_attempts_per_request{bucket="1"} 39252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1412
telemt_me_reconnect_success_total 615
telemt_me_reader_eof_total 632
telemt_me_idle_close_by_peer_total 632
telemt_me_route_drop_no_conn_total 2997765
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2967424
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 821
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
telemt_me_writers_warm_current 19
telemt_desync_total 12804
telemt_desync_full_logged_total 4044
telemt_desync_suppressed_total 8760
telemt_desync_frames_bucket_total{bucket="1_2"} 3412
telemt_desync_frames_bucket_total{bucket="3_10"} 4671
telemt_desync_frames_bucket_total{bucket="gt_10"} 4721
telemt_pool_swap_total 116
telemt_pool_force_close_total 3560
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 35935
telemt_me_writer_removed_unexpected_total 609
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2552
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33641
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3504
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32375
telemt_me_writer_teardown_success_total{mode="normal"} 36193
telemt_me_writer_teardown_noop_total 35946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72139
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.811860
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72139
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 551
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2956404
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 42298956976 (39.39 GB)
telemt_user_octets_to_client{user="hello"} 808887780236 (753.34 GB)
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 118713.6 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4022322
telemt_connections_bad_total 372068
telemt_connections_current 436
telemt_connections_me_current 436
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101196
telemt_upstream_connect_attempt_total 73862
telemt_upstream_connect_success_total 72960
telemt_upstream_connect_fail_total 795
telemt_upstream_connect_attempts_per_request{bucket="1"} 73755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 795
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10296
telemt_me_reconnect_success_total 3690
telemt_me_reader_eof_total 3675
telemt_me_idle_close_by_peer_total 3675
telemt_me_route_drop_no_conn_total 3643712
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3195132
telemt_me_endpoint_quarantine_total 957
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 47
telemt_me_single_endpoint_outage_exit_total 47
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 929
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 13030
telemt_desync_full_logged_total 7317
telemt_desync_suppressed_total 5713
telemt_desync_frames_bucket_total{bucket="1_2"} 2958
telemt_desync_frames_bucket_total{bucket="3_10"} 5116
telemt_desync_frames_bucket_total{bucket="gt_10"} 4956
telemt_pool_swap_total 111
telemt_pool_force_close_total 3139
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 49104
telemt_me_writer_removed_unexpected_total 3604
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6383
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46359
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45965
telemt_me_writer_teardown_success_total{mode="normal"} 52742
telemt_me_writer_teardown_noop_total 49105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101847
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.651273
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101847
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 257
telemt_me_writer_restored_same_endpoint_total 3279
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 3208497
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 43262666114 (40.29 GB)
telemt_user_octets_to_client{user="hello"} 796147134482 (741.47 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 193573.4 (53h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16393431
telemt_connections_bad_total 1661039
telemt_connections_current 1142
telemt_connections_me_current 1142
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 398328
telemt_upstream_connect_attempt_total 87026
telemt_upstream_connect_success_total 86920
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 86937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3033
telemt_me_reconnect_success_total 1609
telemt_me_reader_eof_total 1556
telemt_me_idle_close_by_peer_total 1554
telemt_me_route_drop_no_conn_total 14053652
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13016689
telemt_me_endpoint_quarantine_total 1289
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1457
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_warm_current 30
telemt_desync_total 54011
telemt_desync_full_logged_total 17183
telemt_desync_suppressed_total 36828
telemt_desync_frames_bucket_total{bucket="1_2"} 12049
telemt_desync_frames_bucket_total{bucket="3_10"} 21093
telemt_desync_frames_bucket_total{bucket="gt_10"} 20869
telemt_pool_swap_total 209
telemt_pool_force_close_total 6811
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1066
telemt_me_draining_writers_reap_progress_total 66234
telemt_me_writer_removed_unexpected_total 1497
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5596
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61413
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6341
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59423
telemt_me_writer_teardown_success_total{mode="normal"} 67009
telemt_me_writer_teardown_noop_total 66287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.891460
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1066
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1392
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13016685
telemt_user_connections_current{user="hello"} 1142
telemt_user_octets_from_client{user="hello"} 197505678381 (183.94 GB)
telemt_user_octets_to_client{user="hello"} 3504896340423 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 193574.8 (53h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11941770
telemt_connections_bad_total 1248076
telemt_connections_current 596
telemt_connections_me_current 596
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344962
telemt_upstream_connect_attempt_total 101388
telemt_upstream_connect_success_total 100055
telemt_upstream_connect_fail_total 879
telemt_upstream_connect_attempts_per_request{bucket="1"} 100934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 879
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4468
telemt_me_reconnect_success_total 1919
telemt_me_reader_eof_total 1785
telemt_me_idle_close_by_peer_total 1785
telemt_me_route_drop_no_conn_total 4562402
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8851864
telemt_me_endpoint_quarantine_total 1304
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1476
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_warm_current 26
telemt_desync_total 39041
telemt_desync_full_logged_total 13146
telemt_desync_suppressed_total 25895
telemt_desync_frames_bucket_total{bucket="1_2"} 9673
telemt_desync_frames_bucket_total{bucket="3_10"} 14994
telemt_desync_frames_bucket_total{bucket="gt_10"} 14374
telemt_pool_swap_total 206
telemt_pool_force_close_total 6164
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 64431
telemt_me_writer_removed_unexpected_total 1812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5706
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60396
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5652
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58267
telemt_me_writer_teardown_success_total{mode="normal"} 66102
telemt_me_writer_teardown_noop_total 64456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130558
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.522364
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130558
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1642
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8789600
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 218101059972 (203.12 GB)
telemt_user_octets_to_client{user="hello"} 3973353798039 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 193538.9 (53h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11095302
telemt_connections_bad_total 983642
telemt_connections_current 583
telemt_connections_me_current 583
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345962
telemt_upstream_connect_attempt_total 85643
telemt_upstream_connect_success_total 84082
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 84287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5778
telemt_me_reconnect_success_total 2400
telemt_me_reader_eof_total 2144
telemt_me_idle_close_by_peer_total 2143
telemt_me_route_drop_no_conn_total 5342841
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8383641
telemt_me_endpoint_quarantine_total 1361
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1436
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_me_writers_warm_current 1
telemt_desync_total 38253
telemt_desync_full_logged_total 12677
telemt_desync_suppressed_total 25576
telemt_desync_frames_bucket_total{bucket="1_2"} 9665
telemt_desync_frames_bucket_total{bucket="3_10"} 14645
telemt_desync_frames_bucket_total{bucket="gt_10"} 13943
telemt_pool_swap_total 202
telemt_pool_force_close_total 6060
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 746
telemt_me_draining_writers_reap_progress_total 64836
telemt_me_writer_removed_unexpected_total 2293
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6445
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60617
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58776
telemt_me_writer_teardown_success_total{mode="normal"} 67062
telemt_me_writer_teardown_noop_total 64907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131969
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.846141
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131969
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 746
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2088
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8375580
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 192958279431 (179.71 GB)
telemt_user_octets_to_client{user="hello"} 3479834934437 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 63819.2 (17h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11317268
telemt_connections_bad_total 669888
telemt_connections_current 957
telemt_connections_me_current 957
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 282547
telemt_upstream_connect_attempt_total 60020
telemt_upstream_connect_success_total 56900
telemt_upstream_connect_fail_total 2041
telemt_upstream_connect_attempts_per_request{bucket="1"} 58941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2041
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7814
telemt_me_reconnect_success_total 1283
telemt_me_reader_eof_total 812
telemt_me_idle_close_by_peer_total 811
telemt_me_route_drop_no_conn_total 25300265
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9385395
telemt_me_endpoint_quarantine_total 475
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 511
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 16470
telemt_desync_full_logged_total 4514
telemt_desync_suppressed_total 11956
telemt_desync_frames_bucket_total{bucket="1_2"} 3133
telemt_desync_frames_bucket_total{bucket="3_10"} 6715
telemt_desync_frames_bucket_total{bucket="gt_10"} 6622
telemt_pool_swap_total 66
telemt_pool_force_close_total 2110
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 491
telemt_me_draining_writers_reap_progress_total 20443
telemt_me_writer_removed_unexpected_total 1168
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2679
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18876
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18333
telemt_me_writer_teardown_success_total{mode="normal"} 21555
telemt_me_writer_teardown_noop_total 20462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.966796
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 491
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 828
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 9411244
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 87677576406 (81.66 GB)
telemt_user_octets_to_client{user="hello"} 625184482238 (582.25 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 193545.3 (53h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11052405
telemt_connections_bad_total 965642
telemt_connections_current 814
telemt_connections_me_current 814
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 243704
telemt_upstream_connect_attempt_total 114483
telemt_upstream_connect_success_total 113308
telemt_upstream_connect_fail_total 1001
telemt_upstream_connect_attempts_per_request{bucket="1"} 114309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1001
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73062
telemt_me_reconnect_success_total 3133
telemt_me_reader_eof_total 2825
telemt_me_idle_close_by_peer_total 2823
telemt_me_route_drop_no_conn_total 5269835
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8709896
telemt_me_endpoint_quarantine_total 1307
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1464
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_warm_current 11
telemt_desync_total 46407
telemt_desync_full_logged_total 15920
telemt_desync_suppressed_total 30487
telemt_desync_frames_bucket_total{bucket="1_2"} 9439
telemt_desync_frames_bucket_total{bucket="3_10"} 17766
telemt_desync_frames_bucket_total{bucket="gt_10"} 19202
telemt_pool_swap_total 198
telemt_pool_force_close_total 5772
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 68880
telemt_me_writer_removed_unexpected_total 2848
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5023
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63108
telemt_me_writer_teardown_success_total{mode="normal"} 71769
telemt_me_writer_teardown_noop_total 68881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140650
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.291219
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140650
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 4304
telemt_me_writer_restored_same_endpoint_total 2640
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 8712831
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 196216845189 (182.74 GB)
telemt_user_octets_to_client{user="hello"} 3330172505136 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 130381.6 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11754352
telemt_connections_bad_total 482919
telemt_connections_current 622
telemt_connections_me_current 622
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4767742
telemt_upstream_connect_attempt_total 63103
telemt_upstream_connect_success_total 62643
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 63091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_reconnect_attempts_total 49103
telemt_me_reconnect_success_total 1869
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1545
telemt_me_route_drop_no_conn_total 4099214
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5649485
telemt_me_endpoint_quarantine_total 887
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1002
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31803
telemt_desync_full_logged_total 10861
telemt_desync_suppressed_total 20942
telemt_desync_frames_bucket_total{bucket="1_2"} 6345
telemt_desync_frames_bucket_total{bucket="3_10"} 12554
telemt_desync_frames_bucket_total{bucket="gt_10"} 12904
telemt_pool_swap_total 138
telemt_pool_force_close_total 3982
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 48423
telemt_me_writer_removed_unexpected_total 1591
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3915
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46148
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3541
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44441
telemt_me_writer_teardown_success_total{mode="normal"} 50063
telemt_me_writer_teardown_noop_total 48430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98493
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.721728
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98493
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5641610
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 120140641920 (111.89 GB)
telemt_user_octets_to_client{user="hello"} 2191516227402 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 111352.4 (30h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1551524
telemt_connections_bad_total 36852
telemt_connections_current 456
telemt_connections_me_current 456
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31847
telemt_upstream_connect_attempt_total 52707
telemt_upstream_connect_success_total 52544
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 52679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2316
telemt_me_reconnect_success_total 946
telemt_me_reader_eof_total 935
telemt_me_idle_close_by_peer_total 935
telemt_me_route_drop_no_conn_total 523874
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1379502
telemt_me_endpoint_quarantine_total 939
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 923
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 9495
telemt_desync_full_logged_total 2719
telemt_desync_suppressed_total 6776
telemt_desync_frames_bucket_total{bucket="1_2"} 2833
telemt_desync_frames_bucket_total{bucket="3_10"} 3599
telemt_desync_frames_bucket_total{bucket="gt_10"} 3063
telemt_pool_swap_total 120
telemt_pool_force_close_total 3039
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 44716
telemt_me_writer_removed_unexpected_total 901
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3400
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42258
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2951
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41677
telemt_me_writer_teardown_success_total{mode="normal"} 45658
telemt_me_writer_teardown_noop_total 44720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90378
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.400403
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90378
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 807
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1375284
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 26268023553 (24.46 GB)
telemt_user_octets_to_client{user="hello"} 583436977859 (543.37 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 193550.1 (53h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13376578
telemt_connections_bad_total 1617383
telemt_connections_current 697
telemt_connections_me_current 697
telemt_handshake_timeouts_total 390529
telemt_upstream_connect_attempt_total 76980
telemt_upstream_connect_success_total 76626
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 76844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3051
telemt_me_reconnect_success_total 1529
telemt_me_reader_eof_total 1512
telemt_me_idle_close_by_peer_total 1512
telemt_me_route_drop_no_conn_total 4488074
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10075606
telemt_me_endpoint_quarantine_total 1399
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1465
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_warm_current 17
telemt_desync_total 42258
telemt_desync_full_logged_total 13799
telemt_desync_suppressed_total 28459
telemt_desync_frames_bucket_total{bucket="1_2"} 10270
telemt_desync_frames_bucket_total{bucket="3_10"} 15525
telemt_desync_frames_bucket_total{bucket="gt_10"} 16463
telemt_pool_swap_total 214
telemt_pool_force_close_total 5656
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 69603
telemt_me_writer_removed_unexpected_total 1449
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5428
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65677
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5482
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63947
telemt_me_writer_teardown_success_total{mode="normal"} 71105
telemt_me_writer_teardown_noop_total 69605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140710
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.823847
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140710
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1342
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10042291
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 194998275896 (181.61 GB)
telemt_user_octets_to_client{user="hello"} 4459464614200 (4.06 TB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 193546.4 (53h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11684972
telemt_connections_bad_total 1365563
telemt_connections_current 564
telemt_connections_me_current 564
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 312710
telemt_upstream_connect_attempt_total 104603
telemt_upstream_connect_success_total 103699
telemt_upstream_connect_fail_total 696
telemt_upstream_connect_attempts_per_request{bucket="1"} 104395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 696
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10671
telemt_me_reconnect_success_total 2634
telemt_me_reader_eof_total 2445
telemt_me_idle_close_by_peer_total 2444
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5655370
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8989981
telemt_me_endpoint_quarantine_total 1582
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1467
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_warm_current 11
telemt_desync_total 41933
telemt_desync_full_logged_total 13505
telemt_desync_suppressed_total 28428
telemt_desync_frames_bucket_total{bucket="1_2"} 10838
telemt_desync_frames_bucket_total{bucket="3_10"} 15423
telemt_desync_frames_bucket_total{bucket="gt_10"} 15672
telemt_pool_swap_total 204
telemt_pool_force_close_total 5429
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 69779
telemt_me_writer_removed_unexpected_total 2486
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6813
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65542
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4958
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64350
telemt_me_writer_teardown_success_total{mode="normal"} 72355
telemt_me_writer_teardown_noop_total 69784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 139449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142139
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.504215
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142139
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 2115
telemt_me_writer_restored_fallback_total 137
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 8994551
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 157584402984 (146.76 GB)
telemt_user_octets_to_client{user="hello"} 3504315315886 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 66
```